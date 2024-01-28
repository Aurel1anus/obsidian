对于指针对象不能用“.”，要用“->”。

```
int main() {
	Entity e;
	e.Print;

	Entity* ptr = &e;
	ptr.Print();              //不行
}
```

原因是ptr实际上是一个数值，不是一个对象，所以要用“->“。

