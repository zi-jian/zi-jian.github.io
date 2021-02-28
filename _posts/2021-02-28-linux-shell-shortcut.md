---
layout: page
title: Linux 终端快捷键
permalink: /linux-shell-shortcuts/
date:   2021-02-28 17:37:25 +0800
categories: jekyll update
---

你可能会有这样的疑问：对于有些快捷键，明明有等效的、一个按键就能搞定的操作，为什么非要舍近求远、用两个组合键来实现？

当对键盘、终端命令熟练到一定程度之后，你会发现：手部的频繁移动会影响操作的流畅性，进而影响效率。尤其是涉及方向键、鼠标等操作，不仅耗时耗力，还会增加误触的概率。

`Ctrl + A/E` 移动光标到行首/行尾

`Alt + F/B` 移动光标，向前/向后一个单词

`Alt + Backspace` 剪切光标前一个单词（适用于ksh）

`Ctrl + W` 剪切光标前一个单词（不适用于ksh）

`Ctrl + U/K` 剪切从光标到开头/结尾所有内容

`Ctrl + Y` 粘贴`Ctrl + W/U/K`所剪切的内容

`Ctrl + P/N`上一条/下一条命令，等效于方向键`↑/↓`

`Ctrl + L` 清屏，等效于 `clear` 命令

`Ctrl + H` 删除，等效于 `← Backspace`按键

`Shift + Ins` 粘贴（比鼠标右键/中键快多了）

`Ctrl + R` 搜索历史命令（高效，好用）

`Ctrl + C` 向进程发送`SIGINT`信号，该信号的默认效果是结束进程

`Ctrl + Z` 将进程放到后台挂起，此时可使用`bg`命令让进程在后台继续执行

`Ctrl + D` 表明输入结束。可以用于退出Shell、关闭SSH连接等

上述快捷键依赖于所使用的Shell，适用于`Bash`，部分也适用于QNX的默认Shell `ksh`

当你习惯这些快捷键之后，就会发现之前的操作有多低效

