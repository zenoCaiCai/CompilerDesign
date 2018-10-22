# mini-c 语法支持

## 支持数据类型
##### 整型 int
+ int a = 10;
##### 浮点型 float
+ float flt = 21.97;
##### 字符类型 char
+ char ch = 'A'
##### (Option) 字符串 string
+ char string[] = {'H', 'e', 'l', 'l', 'o', '\0'};  
+ char string[] = "Hello";
+ char* string = "Hello";

## 基本运算
##### 算术运算
算数运算符均为左到右结合；

| 运算符 | 例子 | 优先级 | 结合性 |
| ------ | ------ | ------ | ----- |
| * | c = a * b | 3 | 左到右 |
| / | c = a / b | 3 | 左到右 |
| % | c = a % b | 3 | 左到右 |
| + | c = a + b | 4 | 左到右 |
| - | c = a - b | 4 | 左到右 |

##### 比较运算
| 运算符 | 例子 | 优先级 | 结合性 |
| ------ | ------ | ------ | ------ |
| == | a == b | 7 | 左到右 |
| != | a != b | 7 | 左到右 |
| > | a > b | 6 | 左到右 |
| < | a < b | 6 | 左到右 |
| >= | a >= b | 6 | 左到右 |
| <= | a <= b | 6 | 左到右 |
##### 自增自减运算
| 运算符 | 例子 | 优先级 | 结合性 |
| ------ | ------ | ------ | ------ |
| ++ | a++ | 2 | 左结合 |
| -- | a-- | 2 | 左结合 |
##### 复合赋值运算
| 运算符 | 例子 | 优先级 | 结合性 |
| ------ | ------ | ------ | ------ |
| = | a = b | 14 | 右到左 |
| += | a += b | 14 | 右到左 |
| -= | a -= b | 14 | 右到左 |
| *= | a *= b | 14 | 右到左 |
| /= | a /= b | 14 | 右到左 |
| %= | a %= b | 14 | 右到左 |

## 控制语句
| 运算符 | 例子 | 优先级 | 结合性 |
| ------ | ------ | ------ | ------ |
| () | (a = (b + c)) | 1 | 左到右 |

##### if 语句
##### while 语句
##### (Option)for 语句

## 数组
##### 一维数组
| 运算符 | 例子 | 优先级 | 结合性 |
| ------ | ------ | ------ | ------ |
| [] | a = [1,2] | 1 | 左到右 |

## 注释
##### 行注释
语句//注释内容
##### 块注释
/\*  
  注释内容  
\*/