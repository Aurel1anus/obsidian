##创建并初始化C++对象
在堆上和栈上创建对象的区别       [[C++数组]]
同时栈非常小，可能没有足够的空间去分配 #栈 
栈分配
	Entity* e;
	//{	   //栈分配
	//	Entity entity("Aurelian");
	//	e = &entity;
	//	std::cout << entity.GetName() << std::endl;
	//}

堆分配
		Entity entity = new Entity("Aurelian");
		e = &entity;
		std::cout << entity.GetName() << std::endl;
	}
	在堆上分配要比在栈上分配花更长的时间，且需要手动释放被分配的内存  #堆 