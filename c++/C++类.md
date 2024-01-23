类是一种类型名
类中的内容有可见性，默认类中所有变量都是私有的只有类中的函数才能访问

\#include "Log.h"
\#include <iostream>

class Player {
	public:
		int x, y;
		int speed;
	void Move( int xa, int ya) {
		x += xa*player.speed;
		y += ya*player.speed;

	}
};



int main() {
	Player Player;
	Player.Move(1, 2);
	std::cin.get();
}

类与结构体的比较：
class and struct
在类中变量和函数默认是私有的，
在结构体中默认是公有的。

#include "Log.h"
#include <iostream>

class Log {
public:
	const int LogLevelError = 0;
	const int LogLevelWarning = 1;
	const int LogLevelInfo = 2;
private:
	int m_LogLevel=LogLevelInfo;

public:
	void SetLevel(int level) {
		m_LogLevel = level;
	}

	void Warn(const char* message) {
		if (m_LogLevel>=LogLevelWarning)
			std::cout << "[Warning]:" << message << std::endl;
	}

	void Error(const char* message) {
		if(m_LogLevel>=LogLevelError)
			std::cout << "[Error]:" << message << std::endl;
	}

	void Info(const char* message) {
		if(m_LogLevel>=LogLevelInfo)
			std::cout << "[info]:" << message << std::endl;
	}
};


int main() {
	Log log;
	log.SetLevel(log.LogLevelWarning);
	log.Info("Hello");
	log.Warn("Hello");
	log.Error("Hello");
	std::cin.get();
}
