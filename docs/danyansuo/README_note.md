# 单身狗研究所：第一课 - 理解“单身”的数学与代码定义 🐶

在本节课中，我们将要学习如何从数学和编程的角度，严谨地定义“单身”这一核心概念。我们将通过简单的公式和代码示例，帮助你清晰地理解“单身”状态。

---

## 什么是“单身”？🤔

上一节我们介绍了本课程的目标，本节中我们来看看“单身”的基础定义。从社会关系角度看，“单身”通常指一个人当前未处于恋爱或婚姻关系中。为了在研究和计算中精确使用这个概念，我们需要将其量化。

一个简洁的数学定义是：当一个人的“恋爱关系状态”值为0时，该个体处于单身状态。我们可以用以下公式表示：

**单身状态公式：**
`is_single = (relationship_status == 0)`

其中，`relationship_status` 是一个变量，代表个体的关系状态。0 被约定为表示“无伴侣”或“单身”。

---

## 如何在代码中判断单身？💻

理解了基础定义后，我们可以将其转化为实际的代码逻辑。在不同的编程语言中，判断逻辑是相似的。

以下是判断一个人是否单身的代码示例，我们以Python和JavaScript两种常见语言为例：

**Python 示例：**
```python
# 定义一个表示个人状态的字典
person = {
    "name": "小明",
    "relationship_status": 0  # 0 表示单身
}

# 判断是否为单身
is_single = person["relationship_status"] == 0
if is_single:
    print(f"{person['name']} 是单身。")
else:
    print(f"{person['name']} 不是单身。")
```

**JavaScript 示例：**
```javascript
// 定义一个表示个人状态的对象
let person = {
    name: "小红",
    relationship_status: 0 // 0 表示单身
};

// 判断是否为单身
let isSingle = person.relationship_status === 0;
if (isSingle) {
    console.log(`${person.name} 是单身。`);
} else {
    console.log(`${person.name} 不是单身。`);
}
```

---

## 核心概念总结 📝

本节课中我们一起学习了“单身”的明确定义。

1.  **概念定义**：单身指个体当前未处于恋爱或婚姻关系中的状态。
2.  **数学表达**：通过公式 `is_single = (relationship_status == 0)` 来形式化描述，其中状态值0代表单身。
3.  **代码实现**：在编程中，可以通过判断状态变量是否等于0来识别单身状态，上述Python和JavaScript代码提供了具体示例。

通过本节课的学习，你已经掌握了从理论到实践定义“单身”的方法，这是进行后续所有分析与研究的基础。