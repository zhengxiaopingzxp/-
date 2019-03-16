# dashuju
# 第二章 不是精确性，而是混杂性

> 执迷于精确性是信息缺乏时代和模拟时代的产物。只有5%的数据是结构化且能适用于传统数据库的。如果不接受混乱，剩下95%的非结构化数据都无法被利用，只有接受不精确性，我们才能打开一扇从未涉足的世界的窗户。
### 1、允许不精确
- 数据量的大幅增加会造成结果的不准确，同时，一些错误的数据也会混进数据库。然而，重点是我们能够努力避免这些问题并且学会接受它们。这就是由“小数据”到“大数据”的重要转变之一。
### 2、大数据的简单算法比小数据的复杂算法更有效
**例子（机器翻译案例）**
- 第一阶段：1954年，IBM以计算机中的250个词语和六条语法规则为基础，将60个俄语词组翻译成了英语，结果振奋人心。
- 第二阶段**（两个语言之间的规则）**：IBM的研发人员试图让计算机自己估算一个词或一个词组适合于用来翻译另一种语言中的一个词和词组的可能性，然后再决定某个词和词组在另一种语言中的对等词和词组。
- 第三阶段（**资大大增加和数据量的增多**）：20世纪90年代，将大约有300万句之多的加拿大**议会资料**译成了英语和法语并出版，但是成效不大。
- 第四阶段：无所不包的谷歌翻译系统（优势：有更大更深的数据库；语言的种类多；灵活性大）
### 3、纷繁的数据越多越好
> 大数据不仅让我们不再期待精确性，也让我们无法实现精确性。
### 4、混杂性，不是竭力避免，而是标准途径
> ①互联网上最火的网址都表明，它们欣赏不精确而不会假装精确。
> ②要想获得大规模数据带来的好处，混乱应该是一种标准途径，而不应该是竭力避免的。
### 5、新的数据库设计的诞生
**例子：**Hadoop与VISA的13分钟
- Hadoop（在bending进行分析）通过把大数据变成小模块然后分配给其他机器进行分析，它实现了对超大量数据的处理。-->实现对大数据的分析（不精确性）。
- VISA的13分钟是Hadoop的一个例子。能够将处理两年内730亿单交易所需的时间，从一个月缩减至仅仅13分钟。
