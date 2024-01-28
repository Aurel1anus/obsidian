值复制 (浅复制)：对于指针复制只会复制指向的地址，而不会复制指向地址的内容，在析构函数删除对象的时候会出现对指针的重复删除。

```
class String {
private:
	char* m_Buffer;      //1.指针
	unsigned int m_size;
public:
	String(const char* string) {
		m_size = strlen(string);
		m_Buffer = new char[m_size+1];
		memcpy(m_Buffer, string, m_size);//复制字符串
		m_Buffer[m_size] = 0;
	}

	~String() {
		delete[] m_Buffer;  //2. 析构函数
	}

	friend std::ostream& operator<<(std::ostream& stream, const String& string);
};

std::ostream& operator<<(std::ostream& stream, const String& string) {
	stream << string.m_Buffer;
	return stream;
}

int main() {
	String string = "Aurelian";
	String second = string;      //3.浅复制，对于m_Buffer只复制了地址，两个对象里的指针指向的是同一个地址单元。
	
	std::cout << string << std::endl;
	std::cin.get();
}                                    4.当这两个对象在栈上的生存域结束时，两个对象都调用析构函数删除指针，结果就是对一个内存地址删除了两次，而出现报错。
```
#重载双箭头操作符的代码
#重载方括号操作符的代码



为了解决上面的问题，使用拷贝构造函数。
```
	String(const String& other) :m_size(other.m_size){   //拷贝构造函数
		m_Buffer = new char[m_size + 1];
		memcpy(m_Buffer, other.m_Buffer, m_size + 1);
	}

```



```
	friend std::ostream& operator<<(std::ostream& stream, const String& string)
	//类内友元函数声明。
```

#总是通过const引用去传递对象
