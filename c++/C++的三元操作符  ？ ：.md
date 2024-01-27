三元操作符是if语句的语法糖 #语法糖
性能更好
example1:
	
	if (s_Level > 5)
		s_Speed = 10;
	else
		s_Speed = 5;
	s_Speed = s_Level > 5 ? 10 : 5;//三元操作符

example2:
	std::string rank = s_Level > 10 ? "Master" : "Beginner";//三元操作符
	std::string otherRank;
	if (s_Level > 10)
		otherRank = "Master";
	else
		otherRank = "Beginner";

