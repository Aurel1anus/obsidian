字符串字面量 是在双引号之间的一串字符。

char* name = "Aurelian";
如果你想对name指向的这个字符串“Aurelian”进行修改，那么需要把指针定义改成数组定义
char name \[\]="Aurelian";

在定义字符指针时最好直接定义成 const char* （因为普通的字符指针也修改不了字符串）

字符串字面量永远保存在内存的只读区域内。

\#include <iostream>
#include <string>
#include <stdlib.h>


int main() {
	const char* name = u8"Aurelian";    //utf8
	const wchar_t* name2 = L"Aurelian"; //宽字符 两字节（在不同平台上可变） 
	const char16_t* name3 = u"Aurelian";//两字节 utf16
	const char32_t* name4 = U"Aurelian";//四字节 utf32
	std::cout << strlen(name) << std::endl;
	std::cin.get();
}
