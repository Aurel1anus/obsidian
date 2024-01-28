std::Vector，可以调整数组大小。

当Vector数组的大小超过了初始设置时的大小，它会在内存中创建一个比第一个大的新数组，把所有东西都复制到这里，然后删除旧的那个。

动态数组在内存中是连续的，意味着它在内存中不存在碎片。

```
#include <iostream>
#include <vector>

struct Vector {
	float x, y, z;
};

std::ostream& operator<<(std::ostream& stream, const Vector& ver) {
	std::cout << ver.x << "," << ver.y << "," << ver.z;
	return stream;
}

void Function(const std::vector<Vector>& ver) {

}

int main() {
	std::vector<Vector> ver;   //创建一个Vector结构体动态数组
	ver.push_back({ 1,2,3 }); //初始化数组内容
	ver.push_back({ 4,5,6 });

	for (int i = 0; i < ver.size(); i++) {
		std::cout << ver[i] << std::endl;
	}

	ver.erase(ver.begin + 1); //删除动态数组中的第二个元素

	for (Vector& v : ver) {
		std::cout << v << std::endl;
	}


	std::cin.get();
}
```


vector初始化：


![[Pasted image 20240128134256.png]]