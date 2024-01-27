const是一种（程序员的）承诺

const int* a = new int; //常指针可以改变指向的地址，但是不能改变指向的地址里放的内容 \=\=int const* a

int* const a = new int;//可以改变指针指向的内容，但不能把实际的指针本身重新复制去指向别的东西。

#指针常量  #常量指针

class Entity {
private:
	int m_X, m_Y;
public:
	int GetX() const{  //这里的const意味在这个方法里着不会去改变类里的数据
		return m_X;
	}
};

\#include <iostream>
#include <string>
#include <stdlib.h>

class Entity {
private:
	int m_X, m_Y;
	mutable int var;  //mutable意味着可改变的
public:
	int GetX() const{  //这里的const意味在这个方法里着不会去改变类里的数据
		var = 2;
		return m_X;
	}

	void SetX(int x) {
		m_X = x;
	}
};

void PrintEntity(const Entity& e) {
	std::cout << e.GetX() << std::endl;
}

int main() {
	const int MAX_AGE = 5;
	//a = 2;
	const int* a = new int; //常指针可以改变指向的地址，但是不能改变指向的地址里放的内容 ==int const* a
	int* const a = new int;//可以改变指针指向的内容，但不能把实际的指针本身重新复制去指向别的东西。

	std::cin.get();
}

#mutable

