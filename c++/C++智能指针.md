[[C++的对象生存期（栈作用域生存期）]]

使用智能指针意味着将指针放在堆上存放 #堆 

之所以不使用new、delete、栈指针，使用智能指针，的原因是需要用堆，而且会碰到异常程序不正常退出即使new、delete成对出现也会造成内存泄漏，也因为会忘记delete。

智能指针是自动化实现new、delete的一种方式（自动分配内存和清除内存）：

意味着当你调用new时你不需要调用delete，有时甚至不需要调用new。

它本质上是一个原始指针的包装。

对于所有这些智能指针来说其生存域都取绝于其被定义的域。

1.unique_ptr（作用域指针）：当这个指针超出作用域时，它会被销毁，然后调用delete。

不能复制unique_ptr。

exp：
```
		//std::unique_ptr<Entity> entity(new Entity());
		std::unique_ptr<Entity> entity = std::make_unique<Entity>(); 
		//第二种更安全
```

2.shared_ptr：有计数器的指针，当有shared_ptr被复制赋值给其他的shared_ptr时，计数器加以,当所有shared_ptr都销毁时再释放内存。

```
std::shared_ptr<Entity> sharedEntity = std::make_shared<Entity>();
```

3.weak_ptr：如果复制了shared_ptr给weak_ptr，那么shared_ptr的计数器不会增加。这就意味着当shared_ptr指向的内存被销毁时，weak_ptr有可能还是会存在，你可以问weak_ptr它是否还有效。