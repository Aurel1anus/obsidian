构造函数是一种特殊类型的方法，它在每次实例化对象时都会调用（Init）

class Entity {
public:
	float x, y;
\/\/与类同名的就是构造函数
	Entity() {
		x = 0.0f;
		y = 0.0f;
	}

	Entity(float a,float b) {
		x = a;
		y = b;
	}

	void Print() {
		std::cout << x << "," << y << std::endl;
	}
};

class Log{
private:
	Log(){}  \/\/把构造函数私有化，那么就不能生成实例了
public:
	\/\/Log()=delet; 这样也是同样的效果
	static void Write(){
		}
}
上面的Log只能调用静态函数而不能生成实例


