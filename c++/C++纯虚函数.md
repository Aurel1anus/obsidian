[[C++虚函数]]
纯虚函数允许我们在几类中定义一个没有实现的函数，然后强制子类去实现该函数
virtual std::string GetName() =0//等于0意味着将这个函数变成纯虚函数，意味着它必须在一个子类里实现



\#include <iostream>
#include <string>

class Printable {
public:
	virtual std::string GetClassName() = 0; //接口，纯虚函数。
};

class Entity : public Printable{
public:
	virtual std::string GetName() { return "Entity"; }//std::string 用来定义一个返回字符串对象的函数
	std::string GetClassName() { return "Entity"; }
};

class Player : public Entity {
private:
	std::string m_Name;
public:
	Player(const std::string& name) {
		m_Name = name;
	}

		std::string GetName() override { return m_Name; }
		std::string GetClassName() override { return m_Name; }
};

void PrintName(Entity* entity) {
	std::cout << entity->GetName() << std::endl;
}

class A : public Printable {
public:
	std::string GetClassName() override { return "A"; }
};

void Print(Printable* obj) {
	std::cout << obj->GetClassName() << std::endl;
}



int main() {
	Entity* e = new Entity();
	//PrintName(e);

	Player* p = new Player("Aurelian");
	//PrintName(p);

	Print(e);
	Print(p);

	A* a = new A;
	Print(a); //说明Printable这个接口类并不关心它接受的是什么类。

	std::cin.get();
}