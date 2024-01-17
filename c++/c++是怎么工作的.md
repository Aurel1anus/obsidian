\#include \<iostream\>  ----\#号后面都是预处理语句，处理发生在编译之前
include 的作用在于将 后面的文件找到，然后将这个文件拷贝到现在的文件之中 这种文件被称为头文件

int main（） -----main函数是程序的入口   
main函数不一定需要返回函数

std::cout << "hello World" << std::endl;   -----“<<” 重载运算符 应该将其视为一个函数 其作用是将hello World推送到cout流中

解决方案平台：x86  x64        指的是你编译的代码的目标平台
x86 ：windows 32位

cpp编译后生成obj文件   （vs快捷键ctrl+f7）
link 将所有obj文件合并成exe文件
编译和链接之后生成的obj和exe文件都默认放在x64/debug文件夹中

声明与定义：
声明：告诉编译器某个符号、某个函数是存在的
定义：函数是什么 函数名+函数体
