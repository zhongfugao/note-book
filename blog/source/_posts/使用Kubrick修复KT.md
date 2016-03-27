---
title: 使用Kubrick修复KT
date: 2016-03-27 17:31:14
tags:
---

KT从5.1.2向更高版本升级的时候，出现了网络上常见的`Error 6`错误。问题出现已经有好长时间了，今天决定一定要解决了！

之前一直follow网上比较流行的变砖挽救指南，使用MfgTool+Fastboot的办法，但是当试图进入diags模式的时候卡大树了，等待很久也无法进入diags界面。

另外有一种方式之前也看到过，操作略复杂，今天有时间正好来尝试下。

参考如下两篇文章：
    <http://www.miui.com/archiver/?tid-2135691.html>
    <http://www.mobileread.com/forums/showthread.php?t=206064>

其中第二篇文章已经把流程说的很清楚了，按照这里面的流程操作一遍便通过了。

我是使用USB来做的，具体如下：
1. 下载Live USB Stick和Live CD image
2. 通过win32diskmanager烧录USB Stick，然后把CD image拷贝到USB的`efi/boot/`目录下
3. 使用制作好的U盘启动电脑，按照提示通过usb连接kindle
4. 接下去只要按照提示操作就可以了

整个过程大概二十分钟左右就可以了，然后就可以把KT升级到最新版本了。





