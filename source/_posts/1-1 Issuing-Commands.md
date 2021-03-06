---
title: 1.1 发送指令让Byte动起来 (Issuing Commands)
date: 2016-07-23 12:00:03
categories: 1.指令
tags:
---


简单认识了一下Swift Playgrounds中的虚拟世界后，我们就可以开始写代码让`Byte`做各类任务了。第一个任务的**目标**是让`Byte`移动并拿到那块闪闪发光的宝石。下图标记了在你当前屏幕上看到的内容代表的意思。

![虚拟世界](/images/commands/issuingcommands/1.png)



你想想它应该怎么做才能完成任务？

![虚拟世界](/images/learntocode/2s.png)

`Byte`与宝石间差`3`个地砖，需要向前走`3`步，才能取宝石，因此需要给它发出以下命令：

```swift
moveForward()
moveForward()
moveForward()
collectGem()
```

在命令输入区域输入这四条命令，然后点“Run My Code”，你就成功了。

![发送命令完成](/images/commands/issuingcommands/2.png)

点击Congratulations窗口上的“Next Page”可以进入下一个任务。

