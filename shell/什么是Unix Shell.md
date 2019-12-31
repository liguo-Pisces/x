# 什么是Unix Shell

**Shell** （Unix Shell）是一种命令行解释器，是Unix操作系统下最传统的人机接口。在Shell中，用户可以通过输入程序名称来执行某个程序，最初计算机用户就是通过Shell来让计算机执行任务的。今天在Linux和Mac中大量使用的Shell包括CSH、Bash、ZSH等。

第一个Unix Shell是贝尔实验室的Ken Thompson写的sh，从1971年便开始使用了。Ubuntu、RedHat等Linux发行版中默认的Shell是Bash（Bourne Shell），作者是贝尔实验室的Stephen Bourne，因此得名。Harttle在使用的是Z shell，这是一个非常现代的Shell，兼容于Bash。

## 什么是Shell命令

Shell命令就是我们常说的Linux命令，这些命令可以分为两类：

* 一类是Shell Builtin，这和Shell的类型有关。例如Bash中有`echo`、`pwd`等。
* 一类是PATH下的软件，例如`/usr/bin`下的`ls`、`mkdir`等。

**Shell编程**是一系列Shell（通常指Bash）命令写在一个文件中，以批量地去执行。这个文件便是**Shell脚本**，其中包含了要被顺序执行的Shell命令。

这些Shell脚本一般命名为`*.sh`来表示通过Shell来执行。Shell脚本第一行通常会包含当前脚本文件的解释器，比如`#!/usr/bin/bash`是指用户执行该脚本时，用Bash来解释执行。

