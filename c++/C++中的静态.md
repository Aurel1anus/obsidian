static两种：
1.在类或结构体外使用static关键字
		在类外的static变量或函数，它只对所在的翻译单元（cpp文件）可见
		
2.在类或结构体内使用static关键字
		被定义为static的变量实际上将与类的所有实例共享内存
		当一个实例改变了一个类里的静态变量那么所有实例里的这个静态变量也会变。
		这样的静态变量可以在类之间共享数据或者与整个类有关。
		静态方法不能访问非静态变量。
		在类里定义了静态变量，需要在类外声明。
			static int x, y;	
			...	
			int Entity::x;
			int Entity::y;

局部静态
生存期与变量作用域

void Function() {
	static int i = 0;
	i++;
	std::cout << i << std::endl;
}
//在函数或者类中定义static变量，那么它的生存期就会延长至永远，作用域仍然在当前的函数或类里。
int main() {
	std::cout << "Hello World" << std::endl;
	Function();
	Function();
	Function();
	Function();
	Function();
	std::cin.get();
}

作用域符号  “：：”