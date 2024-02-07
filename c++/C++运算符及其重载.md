如果有这样的需求

```
struct Vector2 {
	float x, y;

	Vector2(float x, float y) :x(x),y(y){
	}

	Vector2 Add(const Vector2& other)const {
		return Vector2(x + other.x, y + other.y);
	}

	Vector2 Multiple(const Vector2& other)const {
		return Vector2(x * other.x, y * other.y);
	}

};

int main() {
	Vector2 position(4.0f,4.0f);
	Vector2 speed(0.5f, 1.5f);
	Vector2 powerup(1.1f, 1.1f)

	Vector2 result = position.Add(speed);
	Vector2 result = speed.Multiply(powerup);
	std::cin.get();
}
```

可以使用运算符重载
```
struct Vector2 {
	float x, y;

	Vector2(float x, float y) :x(x),y(y){
	}

	Vector2 Add(const Vector2& other)const {
		return Vector2(x + other.x, y + other.y);
	}

	Vector2 Multiply(const Vector2& other)const {
		return Vector2(x * other.x, y * other.y);
	}

	//对运算符“+”进行重载
	Vector2 operator+(const Vector2& other)const {
		return Add(other);
	}  

	//对运算符“*”进行重载
	Vector2 operator*(const Vector2& other)const {
		return Multiply(other);
	}

};

int main() {
	Vector2 position(4.0f,4.0f);
	Vector2 speed(0.5f, 1.5f);
	Vector2 powerup(1.1f, 1.1f)

	Vector2 result1 = position.Add(speed);
	Vector2 result2 = speed.Multiply(powerup);
	//对”+”和“*”进行重载后的结构体（或类）运算
	Vector2 result3 = position + speed * powerup;

	std::cin.get();
}
```

对<<进行重载


(std::cout输出的是ostream，相当于把other.x这些粘贴到ostream进去)
```
std::ostream& operator<<(std::ostream& stream, const Vector2& other) {
	stream << other.x << "," << other.y;
	return stream;

}

.....

std::cout << result3 << std::endl;//ok to work
```


对\=\=进行重载

```
	bool opreator == (const Vector2 & other)const {
		return x == other.x && y == other.y;
	}
```

对！=进行重载
```
	bool opreator != (const Vector2 & other)const {
		return !(*this == other);
	}
```
#this


```
ostream& operator<<(ostream& stream, const vector<int> nums) {
    for (int x : nums) {
        stream << x <<",";
    }
    return stream;
}

ostream& operator<<(ostream& stream, const vector<vector<int>> nums) {
    for (auto x : nums) {
        stream << x << endl;
    }
    return stream;
}
```