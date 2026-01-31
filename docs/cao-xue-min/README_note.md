# Python基础教程 1.1

📚 在本节课中我们将要学习Python的基础语法和基本操作。

## 1. Python简介

Python是一种解释型、面向对象、动态数据类型的高级编程语言。它具有语法简洁、易于学习、可读性强等特点。

## 2. 安装Python

以下是安装Python的步骤：

1. 访问Python官方网站：[https://www.python.org/](https://www.python.org/)
2. 下载Python安装包
3. 运行安装包并按照提示进行安装

## 3. Python交互式环境

Python交互式环境（REPL）是一种可以直接在终端中运行Python代码的环境。

以下是启动Python交互式环境的步骤：

1. 打开终端
2. 输入`python`并按回车键

## 4. 变量和数据类型

在Python中，变量用于存储数据。以下是Python中的基本数据类型：

- **数字**：整数（int）、浮点数（float）
- **字符串**：用于存储文本数据
- **布尔值**：True或False

以下是创建变量的示例：

```python
a = 10
b = 3.14
c = "Hello, world!"
d = True
```

## 5. 运算符

Python中的运算符用于对变量进行操作。以下是Python中的基本运算符：

- **算术运算符**：加（+）、减（-）、乘（*）、除（/）、取余（%）、幂（**）
- **比较运算符**：等于（==）、不等于（!=）、大于（>）、小于（<）、大于等于（>=）、小于等于（<=）
- **逻辑运算符**：与（and）、或（or）、非（not）

以下是使用运算符的示例：

```python
x = 5
y = 3

# 算术运算符
result = x + y  # result = 8

# 比较运算符
if x > y:
    print("x大于y")

# 逻辑运算符
if x > y and y > 0:
    print("x大于y且y大于0")
```

## 6. 控制流

Python中的控制流语句用于控制程序的执行顺序。

- **条件语句**：if、elif、else
- **循环语句**：for、while

以下是使用控制流的示例：

```python
# 条件语句
if x > y:
    print("x大于y")
elif x == y:
    print("x等于y")
else:
    print("x小于y")

# 循环语句
for i in range(5):
    print(i)
```

## 7. 函数

函数是Python中的代码块，用于执行特定任务。

以下是定义和调用函数的示例：

```python
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")
```

## 总结

本节课中我们一起学习了Python的基础语法和基本操作，包括Python简介、安装Python、Python交互式环境、变量和数据类型、运算符、控制流以及函数。希望这些内容能帮助你更好地理解Python编程。