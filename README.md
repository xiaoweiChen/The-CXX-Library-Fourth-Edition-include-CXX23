# The C++ Standard Library

*What every professional C++ programmer should know about the C++ standard library.*

 <a href=""><img src="cover.jpg" height="256px" align="right"></a>

* 作者：Rainer Grimm
* 译者：陈晓伟
* 版本：2022-10-30

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

本书是对当前C++23标准ISO/IEC 14882:2023标准库的快速参考。C++23有2100多页，遵循C++20标准。相比之下，C++23和C++17既是不大不小的C++标准更新，而C++14是对C++11的一个补充。

2011年发布的C++11有1300多页。这距离第一个(也是唯一一个C++标准)C++98已经过去了13年。当然，还有2003年发布的C++03，但C++03更多的是作为一个bug修复的C++版本。

这个快速参考的目的是提供C++标准库的简明参考。本书假定读者熟悉C++。若是这样，你会从这本书中得到最大的好处。如对C++很陌生，应该从关于C++核心的教科书开始学习。当掌握了一本关于核心语言的书，就可以通过阅读这本书迈出下一步。为了更便于理解，我提供了许多简短的代码片段将理论和实践进行串联。


## 作者简介

自1999年以来，我一直担任软件架构师、团队领导和讲师。2002年，我创建了公司实习生进修会议。自2002年以来，我一直在教授培训课程。我的第一个教程是关于专有管理软件的，但不久之后我开始教授Python和C++。我喜欢在业余时间写一些关于C++、Python和Haskell的文章，也喜欢在会议上发言。我每周都会在我的英文博客[Modernes Cpp](https://www.modernescpp.com/)和由Heise Developer托管的[German blog](https://www.grimm-jaud.de/index.php/blog)上发表文章。

自2016年以来，我一直是一名独立讲师，讲授有关现代C++和Python的研讨会。我已经用各种语言出版了几本关于现代C++的书，特别是关于并发性的书。由于我的职业，我一直在寻找教授现代C++的最佳方法。



## 本书相关

* Github地址：https://github.com/xiaoweiChen/The-CXX-Library-Fourth-EDdition-include-CXX23

* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html
  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：

    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "C++-Standard-Library".tex`

  * 为了内容中表格和目录索引能正常生成，需要至少两次连续编译

* vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016

