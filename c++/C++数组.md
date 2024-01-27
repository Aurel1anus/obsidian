指针是c++数组工作方式的基础
设置安全检测，确保写的东西没有超出数组界限（在debug下会报错，在release下不会报错）
数组名是指向数组首地址的指针变量。

在堆上和栈上存放数组的区别：
在栈（steak）上创建，那么程序在运行到花括号之后，数组就会自动销毁；
在堆（heap）上创建，直到我们程序把它销毁之前，它都处于活动状态，需要使用delet关键词来删除它。 #堆  #栈 
在堆上（new关键字创建）和栈上的数组最关键的区别就是生存期。
如果不用new关键字就不要用delete关键字。  #newdelete
（ex：如果你想返回一个数组，这个数组是在函数中创建的，那么就一定要用new来创建）
但是在栈上创建数组不用在内存中跳来跳去，性能更好。

\#include <iostream>
#include <string>
#include <array>



class Entity{
public:
	static const int size = 5; //自己维护数组
	int example[size];

	std::array<int, 5> another;

	Entity() {

		int a[5];
		int count = sizeof(a) / sizeof(int);//5
		for (int i = 0; i < another.size(); i++) {
			example[i] = 2;
		}
	}
};

class Player  {

};

int main() {

	Entity e;

	int example[5];

	int* another = new int[5];
	for (int i = 0; i < 5; i++)
		another[i] = 2;
	delete[] another;


	std::cout <<e.example[2] << std::endl;
	std::cout << e.size << std::endl;


	std::cin.get();
}

#数组CPP
#stdarray






