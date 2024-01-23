子类继承父类是为了防止代码重复。
子类是父类的超集，子类将包含父类所有的东西
#include <iostream>

class Entity {
public:
	float X, Y;

	void Move(float xa, float ya) {
		X += xa;
		Y += ya;
	}
};

class Player : public Entity {
public:
	const char* Name;

	void PrintName() {
		std::cout << Name << std::endl;
	}
};

int main() {
	std::cout << sizeof(Entity) << std::endl;//两个32位系统下的float变量 4+4=8
	std::cout << sizeof(Player) << std::endl;//两个32位系统下的float变量加上一个指针变量（4字节）4+4+4=12
	Player player;
	player.Move(5, 5);

	std::cin.get();
}