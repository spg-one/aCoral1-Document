# 1. Prerequisites
* 操作系统课程
* Linux基本操作
* 汇编语言
* C语言
* 一点点的数电和模电知识

# 2. Learning Route
![](pic/Learning%20Route.png)

学习aCoral的单核版本（aCoral-Ⅰ），可以通过阅读[aCoral-Ⅰ overview](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20Overview)，对aCoral单核版本有一个大致的了解。

接下来，可以从aCoral在mini2440开发板的上电启动过程（[aCoral-Ⅰ Boot](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20Boot)）开始学习，搞明白在按下开发板的开关之后，aCoral是如何一步一步启动的。

掌握了上电启动流程之后，就可以进行对aCoral最重要的部分——内核（[aCoral-Ⅰ Boot](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20Kernel)）的学习了。内核是整个操作系统的核心，包含线程管理、中断管理等基本模块。上电启动完毕之后，内核就移植运行在开发板之上，管理所有的硬件、软件资源。

仅仅有内核的话，aCoral作为一个操作系统还是略显简陋，所以在内核之外，aCoral还包含了文件系统（[aCoral-Ⅰ FS](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20FS)）、网络通信功能（[aCoral-Ⅰ LWIP](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20LWIP)）、用户图形界面（[aCoral-Ⅰ GUI](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20GUI)）、驱动（[aCoral-Ⅰ Driver](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20Driver)）以及各类应用程序（[aCoral-Ⅰ APP](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20APP)）。

最后，对于开发者，还需要学习如何来使用、开发aCoral操作系统，这部分内容可以在[aCoral-Ⅰ Dev](https://github.com/spg-one/aCoral1-Document/tree/master/aCoral-%E2%85%A0%20Dev)找到。

以上所有内容，都可以在对应名字的目录下面找到学习文档。