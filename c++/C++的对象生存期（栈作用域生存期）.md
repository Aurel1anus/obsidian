错误示范（因为把数组创建在了栈上）

```
int* CreateArray() {
	int array[50];
	return array;
}
```

正确示范（在堆上创建数组）

```
int* CreateArray() {
	int array[50]=new int[50];
	return array;
}
```

或者也可以传指针进去



智能指针的手动写法：

```
class ScopedPtr {
private:
	Entity* m_ptr;
public:
	ScopedPtr(Entity* m_ptr) :m_ptr(m_ptr) {}

	~ScopedPtr() {
		delete m_ptr;
	}
};

int main() {
	
	{
		ScopedPtr e(new Entity());
	}

	std::cin.get();
}
```

#智能指针

