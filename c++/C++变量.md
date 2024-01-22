创建变量时，变量将会被储存在内存中，两个地方 --堆和栈
C++中变量真正的区别是大小（size）
int 的数据表示范围从-21亿到+21亿 ) (4字节，带符号 31+1)
char 1字节 ，short 2字节 ， int 4字节， long 4字节，long long 8字节
float 4字节， double 8字节
在数据后面加f才是定义为float类型，不然就是double类型。 “ float var = 5.5f;”
bool 1字节(不能创建1字节的变量，应为计算机用字节寻址，但是可以1字节定义8个bool)
bool* 代表指针  bool& 代表引用
