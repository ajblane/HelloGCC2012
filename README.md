# HelloGCC2012

## Port GDB to a New Architecture

**演讲者： 齐尧** codesourcery/mentorgraphics

简介：我们会介绍如何把GDB移植到一个新的体系结构上，包括支持改体系结构的断点，单步，还会介绍如何支持该体系结构的prologue 分析和epilogue 分析，最后我们介绍在Linux 之上，我们需要做的移植工作，比如对plt stub的支持和signal trampoline的支持。

演讲幻灯片下载： https://github.com/lazyparser/HelloGCC2012

```
<embed src="http://www.tudou.com/v/cFLJMmqkcec/&#038;rpid=281380&#038;resourceId=281380_05_05_99&#038;bid=05/v.swf" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" wmode="opaque" width="480" height="400"></embed>
```

## LLVM: Another Toolchain Platform

**演讲者：杨勇勇**

中国科学院自动化研究所在读博士生，三年级。感兴趣的领域包括：嵌入式系统开发平台、大规模数据计算、软件工程、编译优化技术、代码生成及调度算法、操作系统等等。

简介：自动化研究所下属的“国家专用集成电路设计与研究工程技术中心”目前正在开发一款面向极大数据量和运算量的SoC平台原型，负责数据处理的核心是一个自主设计、概念新颖的多运算核系统。本人负责的工作内容是构建该处理核心的软件工具链，包含C语言编译器、汇编器、反汇编器、链接器、调试器等。
我们选择LLVM作为编译工具的实现基础。该话题演讲讨论的是一套基本的软件开发平台，我们会介绍LLVM系统结构，如何实现一个LLVM的后端，以及通过LLVM的MC层整合汇编器/反汇编器，并在最后简单讨论链接器和符号调试器。

```
<embed type="application/x-shockwave-flash" width="480" height="400" src="http://www.tudou.com/v/0B-Su5enE9I/&amp;rpid=281380&amp;resourceId=281380_05_05_99&amp;bid=05/v.swf" allowfullscreen="true" wmode="opaque"></embed>
```

TODO: 演讲者信息和演讲主题介绍内容不全

# HelloGCC 2012 活动通知

HelloGcc工作组由自由软件爱好者和自由软件工作者于2007年在北京成立，旨在营造一个自由，开放，共享的技术社区，讨论GNU底层系统工具（包括GCC，GDB，BINUTILS等），以及其它开源工具（比如LLVM，QEMU等等）的技术知识，为工作和学习提供帮助，并为自由软件社区做出贡献。

我们每年都会举办一次技术讨论会。今年的活动暂定为在11月10日（周六）举办（具体地点待定）。现在向大家提前发出征稿通知，如果你有兴趣来做相关的技术话题报告，欢迎提前与我们联系。话题范围包括：

* 原创工作，或者对他人工作的介绍
* 研究性的，或者工程性的
* 代码讲解，程序演示
* 等等

我们只需要提前获得演讲者的幻灯片（并经演讲者同意后，发布在网上）。如果你打算同时提供文字稿件，当然更好。整个活动是免费的，我们希望能够获得一些赞助，以用于对演讲者提供酬谢和对社区的发展提供支持。投稿，赞助，以及其它活动相关的事宜，请发送邮件到邮件列表：

* hellogcc@freelists.org

在邮件列表中讨论。

附注：

2011年演讲话题：

1、Introduction to GCC Backend
2、GNU Tools for ARM Embedded Processors
3、多核时代更快断点 — Displaced stepping以及对Thumb-2指令集的实现
4、TCG与LLVM生成二进制代码性能分析
5、走进GCC插件时代

2010年演讲话题：

1、内存管理机制与优化
2、调试器的断点机制的探讨
3、针对嵌入式CPU的Binutils移植
4、GCC编译器图形化实现与讨论
5、How To Port GNU ToolChain
6、Linux Kernel GDB tracepoint module演示

2009年演讲话题：

1、使用GCC编译器分析和优化程序的数据局部性
2、GCC Internals and Porting
3、gdbproxy: An open source GDB stub for Blackfin
4、GDB reverse debug and process record and replay target

交流平台：

* 博客地址，http://www.hellogcc.org
* 邮件列表，http://www.freelists.org/archive/hellogcc
* IRC房间， #hellogcc（freenode）
