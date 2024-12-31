---
title: 从零开始的 Java 语言配置过程
publishDate: 2024-10-18 18:30:20
description: 统一的环境配置指南～
tags: [vscode, java]
language: 中文
draft: true
---

## 写在前面

写下该教程的目的是为了配置 CS61b 课程的轻量开发环境，IDEA 真的带不动。

## 安装 JDK

首先为了方便地管理环境，需要一个类似于 nvm 的环境管理工具。这里我的选择是 [sdkman](https://sdkman.io/)，根据官网教程进行安装即可。

我选择的 Java 版本是 17，安装命令如下：

```bash
sdk install java 17.0.12-tem
```

安装好了之后可以通过 `which java` 查看安装路径。

## 配置 VSCode

根据 VSCode 的官方教程安装即可：[官方教程](https://code.visualstudio.com/docs/java/java-tutorial#_running-and-debugging-your-program)。我目前的要求就是运行和调试，其余的功能可以自行尝试。
