---
layout: post
title:  "vi文本编辑常用命令"
date:   2014-03-23 23:09:28
tags: [Linux, Vi, Vim]
---

vi是Linux及类Unix系统中主流的命令行文本编辑器，功能极为强大，vim是增强版本的vi

vim有三种工作模式：

* 命令模式（常规模式）
* 插入模式
* ex模式

命令模式常用指令：

* i 插入
* o 在当前行下插入新行
* dd 删除当前行
* yy 复制一行
* p 粘贴
* u 撤销上一个操作
* r 替换当前字符
* / 搜索

模式常用命令：

* :w 保存修改
* :q 退出
* :q! 强制退出，不保存修改
* :x 保存并退出，相当于:wq
* :set number 显示行号
* :! 执行系统命令
* :sh 切换到命令行，使用 ctrl + d 切换回vim