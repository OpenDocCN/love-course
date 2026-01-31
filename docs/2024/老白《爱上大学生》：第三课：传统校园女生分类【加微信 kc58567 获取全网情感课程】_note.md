# 老白《爱上大学生》：第三课：传统校园女生分类

大家好，我是老白，欢迎来到我们最新的校园课程。想在校园中追求女生，首先你要清楚校园里有哪几类女生，然后再根据自己的实际情况来判断自己可能会比较容易搞定哪一类女生。本节课我来讲讲对校园女生的分类。

## 第一类：校花

在戏里或者邻近几个班级里小有名气的女生，以及军训中或者是运动会中凭借身材样貌脱颖而出的女生，俗称校花。这类型的女生可以说是男人们最关心的类型了。有时候你可能未见其面，先闻其名。

**公式**：校花 = 小有名气的女生 + 身材样貌突出的女生

**代码**：class 校花:
    def __init__(self, name, popularity, appearance):
        self.name = name
        self.popularity = popularity
        self.appearance = appearance

## 第二类：女学霸

这类型的女生具有卓越的学习能力，普通人很难从智商上碾压他们，他们把时间放在书本上。所以有的时候不太懂得社交和不熟的人也不太开得起玩笑。

**公式**：女学霸 = 具有卓越学习能力 + 专注于学习

**代码**：class 女学霸:
    def __init__(self, name, intelligence, focus):
        self.name = name
        self.intelligence = intelligence
        self.focus = focus

## 第三类：文艺女生

这类女生通常具备某项才艺，唱歌跳舞、琴棋书画等等。他们基本上是通过艺考进的大学的，在才艺方面呢，他们是相当有自信的。

**公式**：文艺女生 = 具备才艺 + 通过艺考进入大学

**代码**：class 文艺女生:
    def __init__(self, name, talent, entrance_exam):
        self.name = name
        self.talent = talent
        self.entrance_exam = entrance_exam

## 第四类：女汉子

很多女生热爱称自己为女汉子，他们生来不拘小节，性格开朗直爽，心态乐观，内心强大，能够独挡一面。

**公式**：女汉子 = 不拘小节 + 开朗直爽 + 乐观

**代码**：class 女汉子:
    def __init__(self, name, unbound, open, optimistic):
        self.name = name
        self.unbound = unbound
        self.open = open
        self.optimistic = optimistic

## 第五类：宅女

现在大学里的宅女数量也不断的增多。他们的生活圈子小，接触的人也少，思想上相对来说比较单纯，课余时间呢也不会参加什么社交活动或者聚会，通常喜欢待在宿舍看动漫、看电影、看剧或者玩游戏。

**公式**：宅女 = 生活圈子小 + 思想单纯 + 喜欢宅在宿舍

**代码**：class 宅女:
    def __init__(self, name, small_circle, simple, stay_at_home):
        self.name = name
        self.small_circle = small_circle
        self.simple = simple
        self.stay_at_home = stay_at_home

## 第六类：富家女

你在学校可能有一些任性的有钱的富家女。有的时候你甚至发现这些富家女跟一些价值没那么高的男生在一起了。

**公式**：富家女 = 有钱的富家女 + 注重感情交流

**代码**：class 富家女:
    def __init__(self, name, rich, emotional):
        self.name = name
        self.rich = rich
        self.emotional = emotional

本节课中我们一起学习了校园中女生的六大分类，希望对你了解和追求女生有所帮助。