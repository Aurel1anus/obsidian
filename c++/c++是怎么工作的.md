\#include \<iostream\>  ----\#号后面都是预处理语句，处理发生在编译之前
include 的作用在于将 后面的文件找到，然后将这个文件拷贝到现在的文件之中 这种文件被称为头文件

int main（） -----main函数是程序的入口   
main函数不一定需要返回函数

std::cout << "hello World" << std::endl;   -----“<<” 重载运算符 应该将其视为一个函数 其作用是将hello World推送到cout流中
