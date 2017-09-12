ThoughtWorks 2018校园招聘作业
===
题目：羽毛球馆
---
程序描述
---
运行结果
---
程序代码
---
总结
---
我定义了一个基础类`Gymnasium`,描述每次输入字符的处理和存储。题目主要设计就是考虑预约记录的存储问题，为了方便存储和读取，我运用类似`HashMap`的思想，考虑到每天预约都是整点进行，所以我定义了一个`OrderTable`类，名为预定数组表，将同一天的记录都存在这个数组表中，且数组中元素存放`OrderLinkCancel`类，是一个链表，用来存放在该时间点预约的用户和取消的记录，如图所示。
![](https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif)
