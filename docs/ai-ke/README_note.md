# Python基础教程 1.1

👋 欢迎来到Python基础教程！在本节课中，我们将学习Python的基本语法和概念。

## 概述

Python是一种广泛使用的编程语言，以其简洁明了的语法和强大的库支持而闻名。本教程旨在帮助初学者快速掌握Python的基础知识。

## 安装Python

在开始之前，确保你的计算机上安装了Python。你可以从Python的官方网站下载并安装最新版本。

```bash
# 在命令行中安装Python
pip install python
```

## Python基础语法

以下是Python的一些基础语法：

### 变量和数据类型

在Python中，变量不需要声明类型。以下是一些基本的数据类型：

- **整数**：`int`
- **浮点数**：`float`
- **字符串**：`str`
- **布尔值**：`bool`

**公式**：`x = 5`  # 整数变量
`y = 3.14`  # 浮点数变量
`name = "Alice"`  # 字符串变量
`is_valid = True`  # 布尔变量

### 运算符

Python支持各种运算符，包括算术运算符、比较运算符和逻辑运算符。

- **算术运算符**：`+`, `-`, `*`, `/`, `%`
- **比较运算符**：`==`, `!=`, `<`, `>`, `<=`, `>=`
- **逻辑运算符**：`and`, `or`, `not`

**代码**：

```python
# 算术运算
result = 5 + 3  # 8
result = 5 - 3  # 2
result = 5 * 3  # 15
result = 5 / 3  # 1.666...

# 比较运算
is_equal = 5 == 5  # True
is_not_equal = 5 != 5  # False

# 逻辑运算
is_true = True and False  # False
is_false = False or True  # True
```

### 控制流

Python使用`if`语句来实现条件判断。

**代码**：

```python
# if语句
if 5 > 3:
    print("5大于3")
```

### 循环

Python支持`for`和`while`循环。

**代码**：

```python
# for循环
for i in range(5):
    print(i)

# while循环
count = 0
while count < 5:
    print(count)
    count += 1
```

## 总结

本节课中，我们一起学习了Python的基础语法和概念。在下一节课中，我们将学习Python的数据结构和函数。