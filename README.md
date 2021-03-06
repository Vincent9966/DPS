# 题目概述

在Python中写一个命令行工具,显示如何获取一组个人数据集(姓名、地址、电话号码)并且序列化/反序列化它们至少2格式,并将其显示在至少两种不同的方法(不需要使用一个GUI框架，只要文本输出/ HTML或任何其他人类可读的格式就可以了)。  不需要支持手动数据输入—您可以手动地用您选择的格式之一编写一个文件来提供您的输入测试数据。

以一种对开发人员来说很容易的方式来编写它:

- 添加对其他存储格式的支持。
- 查询当前支持的格式列表。
- 为支持的格式之一提供一个可选的读取/写入器。
- 合理的单元测试覆盖率



这应该在理想情况下展示面向对象设计和设计模式知识。



大概意思：

查询当前可以支持的格式列表、选择读取还是写入，选择什么样的格式进行操作以及使用什么软件打开（打开之前进行反序列化生成对应的数据），操作完毕之后回到控制台，程序对刚刚更新的数据进行序列化（对于写入的情况）。并且要有一个合理的单元测试率，能够展示自己对面向对象设计和设计模式知识的运用。

