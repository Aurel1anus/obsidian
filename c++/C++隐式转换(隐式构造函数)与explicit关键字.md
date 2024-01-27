```
class Entity {
private:
	String m_Name;
	int m_Age;
public:
	Entity(int age) : m_Name("UnKnown"),m_Age(age){}
	Entity(const String& name):m_Name(name),m_Age(-1){}

	const String& GetName() const { return m_Name; }
 };
```



```
	Entity e = String("Aurelian"); 
//隐式转换，将std：：string转变成Entity对象，因为有Entity（const String& name)这个构造函数。
	Entity f = 20;                 
//隐式转换，将int转变成Entity对象，因为有Entity（int age）这个构造函数。
```

```
explicit Entity(int age) : m_Name("UnKnown"),m_Age(age){}
```
如果在构造函数上用了explicit那么就隐式转换就不会生效。