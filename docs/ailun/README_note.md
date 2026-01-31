# Python基础教程 1.1

👋 欢迎来到Python基础教程！在本节课中，我们将学习Python的基本语法和概念。

## 概述

Python是一种广泛使用的编程语言，以其简洁明了的语法和强大的库支持而闻名。本教程旨在帮助初学者快速掌握Python的基础知识。

## 安装Python

首先，您需要在您的计算机上安装Python。您可以从Python的官方网站下载并安装最新版本的Python。

```bash
# 在命令行中运行以下命令
pip install python
```

## Python基础语法

以下是Python的一些基础语法：

### 变量和数据类型

在Python中，变量不需要声明类型。以下是一些常见的数据类型：

- **整数**：`int`
- **浮点数**：`float`
- **字符串**：`str`
- **布尔值**：`bool`

```python
# 变量和数据类型
age = 25
height = 5.9
name = "John"
is_student = True
```

### 运算符

Python支持各种运算符，包括算术运算符、比较运算符和逻辑运算符。

- **算术运算符**：`+`, `-`, `*`, `/`, `%`
- **比较运算符**：`==`, `!=`, `<`, `>`, `<=`, `>=`
- **逻辑运算符**：`and`, `or`, `not`

```python
# 运算符
result = 10 + 5  # 等于15
age = 25
is_adult = age >= 18  # 等于True
```

### 控制流

Python使用`if`语句来实现条件判断。

```python
# 控制流
if age >= 18:
    print("You are an adult.")
else:
    print("You are not an adult.")
```

### 循环

Python支持`for`和`while`循环。

```python
# 循环
for i in range(5):
    print(i)

count = 0
while count < 5:
    print(count)
    count += 1
```

## 总结

本节课中，我们一起学习了Python的基础语法和概念。在下一节课中，我们将学习Python的函数和模块。