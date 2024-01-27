new关键字不仅仅分配空间而且还调用函数。

new是一个操作符。
```
`Entity* e = （Entity*）malloc（sizeof（Entity））;`
```

==相当于==
```
`Entity* e = new Entity();`
```

这两个的唯一区别就是上面只分配了内存，而下面的还调用了构造函数。

```
int* b = new int[50];//200 bytes 
delete[] b;
```

#newdelete 

用new一定要用对应的delete。