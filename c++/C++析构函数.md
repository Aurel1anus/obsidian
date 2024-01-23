	~Entity() {
		std:: cout<< "Destroyed Entity!" << std::endl;
	}
为什么要写析构函数：
如果在类的使用或者构造中分配了内存，那么就需要手动去析构，防止内存泄漏