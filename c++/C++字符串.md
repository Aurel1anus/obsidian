字符--char  字符串--字符数组  [[C++数组]]
在内存中字符串结束之后，有一个结束字节00，代表该字符串结束（空终止字符）。 #空终止字符

cpp string [cplusplus.com/reference/string/string/](https://cplusplus.com/reference/string/string/)


#include <iostream>
#include <string>
#include <array>



class Entity{

	
};

class Player  {

};

void PrintString(const std::string& string) {   //&引用意味着不会复制字符串，const意味我们承诺不会在这修改
	std::cout << string << std::endl;

}



int main() {
	//const char* name = "Aurelian";
	std::string name = "Aurelian"; //const char[9]
	name += "Hello";
	char name2[7] = { 'C','h','e','r','n','o',0}; //手动添加空终止符
	std::cout << name << std::endl;

	std::cin.get();
}