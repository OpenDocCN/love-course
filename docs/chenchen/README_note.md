# 课程名称：Batre 🦇

在本节课中，我们将要学习Batre的基本概念、核心功能以及如何使用它。Batre是一个用于构建命令行界面的Python库，它简化了参数解析和命令组织的过程。

## 什么是Batre？ 🤔

上一节我们介绍了课程目标，本节中我们来看看Batre是什么。Batre是一个Python库，它允许开发者轻松地为他们的Python脚本创建命令行界面。它通过装饰器和类来定义命令和参数，使得代码结构清晰且易于维护。

## 核心概念与安装 🔧

理解了Batre的用途后，我们需要了解其核心概念并完成安装。Batre的核心是使用装饰器 `@command` 来标记一个函数作为命令行命令，并使用 `@argument` 装饰器来定义命令接受的参数。

以下是安装Batre的步骤：

1.  确保你的系统已安装Python。
2.  打开终端或命令提示符。
3.  运行命令：`pip install batre`

## 创建你的第一个Batre应用 🚀

安装完成后，我们可以开始创建第一个Batre应用。我们将创建一个简单的“Hello World”程序，它接受一个名字作为参数。

以下是如何编写代码：

```python
from batre import command, argument

@command
@argument("name", help="你的名字")
def hello(name):
    """一个简单的问候命令。"""
    print(f"Hello, {name}!")

if __name__ == "__main__":
    hello()
```

在这段代码中：
*   `@command` 装饰器将 `hello` 函数声明为一个命令行命令。
*   `@argument` 装饰器定义了一个名为 `name` 的参数，并提供了帮助文本。
*   函数内部的 `print` 语句是命令执行的具体操作。
*   最后的 `if` 语句确保当脚本直接运行时，Batre能够解析命令行参数并调用相应的函数。

## 运行与测试 ▶️

代码编写完成后，我们需要知道如何运行它。将上述代码保存为一个Python文件，例如 `app.py`。

以下是运行命令的示例：

*   在终端中运行基础命令：`python app.py --name World`
*   查看自动生成的帮助信息：`python app.py --help`

运行 `python app.py --name World` 后，终端将输出：`Hello, World!`。

## 总结 📝

本节课中我们一起学习了Batre库的基础知识。我们了解了Batre是一个用于构建Python命令行界面的工具，掌握了其核心装饰器 `@command` 和 `@argument` 的用法，并成功创建并运行了一个简单的命令行应用。通过Batre，我们可以更高效、更结构化地开发命令行程序。