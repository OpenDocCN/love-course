# **不要看女生说了什么，而是看女生做了什么 - P1 - 池子的恋爱日记 - BV1dx4y17779**

## 概述
在本节课中，我们将学习如何通过观察女生的行为来判断她的感情倾向。

## 核心概念
**公式**：女生行为 = 情感倾向 + 环境因素

## 分析女生行为的方法

### 方法一：观察行为对关系的推进
**描述**：观察女生的行为是否在推进你们之间的关系。例如，如果你给女生发了一大段信息，而她对你冷淡敷衍，这通常意味着她不喜欢你。

**代码**：
```python
def relationship_progression(action, response):
    if action == "send_message" and response == "cold":
        return "dislike"
    else:
        return "unknown"
```

### 方法二：行为对比
**描述**：将女生的当前行为与她之前的行为进行对比。例如，如果女生之前对你很热情，但现在变得冷淡，这可能意味着她对你的好感在减少。

**代码**：
```python
def behavior_comparison(current, previous):
    if current == "cold" and previous == "hot":
        return "decreasing_interest"
    else:
        return "increasing_interest"
```

### 方法三：观察配合度
**描述**：观察女生是否愿意配合你的请求。一般来说，一个女生越喜欢你，就越愿意配合你。

**代码**：
```python
def cooperation_level(interaction_level, cooperation):
    if interaction_level == "high" and cooperation == "low":
        return "dislike"
    else:
        return "unknown"
```

## 总结
本节课中我们一起学习了如何通过观察女生的行为来判断她的感情倾向。通过分析行为对关系的推进、行为对比以及观察配合度，我们可以更好地理解女生的真实想法。