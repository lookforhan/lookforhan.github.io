---
layout: post
title: a bug when matlab use xlswrite
data: 2019-01-23
---
# 问题

最近在写一篇小论文，没有更新博客。

这个问题是我在为小论文写程序的时候发现的。我为了记录程序运行结果，在某个函数中使用了xlswrite函数，在单元测试时也没有发现问题。但是在大规模计算，多次调用该函数时，出现了异常错误。错误原因尚未确定。

猜测是matlab本身的原因。

matlab版本为2013a。
