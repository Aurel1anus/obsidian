\#include <iostream>
#include <string>
class Entity {
public:
	virtual std::string GetName() { return "Entity"; }//std::string 用来定义一个返回字符串对象的函数
};

class Player : public Entity {
private:
	std::string m_Name;
public:
	Player(const std::string& name) {
		m_Name = name;
	}

		std::string GetName()  override { return m_Name; }
};

void PrintName(Entity* entity) {
	std::cout << entity->GetName() << std::endl;
}

int main() {
	Entity* e = new Entity();
	PrintName(e);

	Player* p = new Player("Aurelian");
	PrintName(p);

	std::cin.get();
}

在Player这个Entity的子类中，重写了GetName这个方法

重载：
父类中：virtual std::string GetName() { return "Entity"; }
子类中std::string GetName()  override { return m_Name; }