---
title: 2 使用一个新命令
date: 2016-07-23 16:39:18
tags:
---


本关卡跟上一个很类似，但你发现这次想让`Byte`走到宝石那儿的话，你需要让他向左转一次。这个动作依靠给它发送新的`turnLeft()`命令来实现：

![左转命令](/images/addinganewcommand/1s.png)

很简单，你自己试一下。然后再点“Next Page”继续下一关。


> 注意，`Byte`需要走的步数只跟它前进方向需要跨过的地砖数有关，上下台阶不需要额外算步数，如图所示。

![前进步数问题](/images/addinganewcommand/2s.png)
