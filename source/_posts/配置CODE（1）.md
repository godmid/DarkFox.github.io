---
title: VS Code编写Keil工程
tags: code
top: 17
abbrlink: 8eea644e
date: 2020-12-06 15:23:11
---

### 前言

keil 作为最经典的入门IDE，尽管功能强大，但是界面不太友好，也不支持常用的代码自动补全，代码重构等基本功能，代码量多了以后，程序的编写，调用，查看，修改等都很不方便。之前看到网上很多人都用的code进行的开发，于是我也搞了一个。我将过程记录下来，方便自己和其他人查阅和学习。

通常换了一个开发工具软件，需要重新搭建开发环境，这是很麻烦的事情，但是使用VS Code + Keil Assistant插件可以让这个过程变得非常简单。十分感谢写这个插件的大神！

另外，博客里的图片是我随手从网上截取的，只是个参考例子作用，版本可能较老旧，小伙伴们下载的时候选择最新的即可

<!--more-->

***

### 大致过程

+ 1、首先下载一个CODE的安装包，用搜索引擎查一下，找到官方的安装包

  <img src="https://s3.ax1x.com/2020/12/15/rMqAW6.png" alt="rMqAW6.png" style="zoom: 80%;" />

+ VS Code官网：https://code.visualstudio.com/

+ 2、其次按照说明以及需求安装

+ 3、配置环境

+ 4、安装插件

  ***

### 中文化

大部分刚入手的的小伙伴可能看不懂英文，所以可以下载一个中文的插件

1、在插件里面搜索chinexe就可以找到中文化的插件了

<img src="https://s3.ax1x.com/2020/12/15/rMLoUs.jpg" alt="rMLoUs.jpg" border="0" style="zoom: 50%;" /><img src="https://img-blog.csdnimg.cn/20190118174440530.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L211bXUxOTk4,size_16,color_FFFFFF,t_70" alt="2" style="zoom:50%;" />

<img src="https://s3.ax1x.com/2020/12/15/rMOWJ1.md.png" alt="rMOWJ1.md.png"  />

2、安装好插件后可以使用快捷键Shift+Ctrl+P，然后输入Configure Language

3、选中打开之后就会打开 locale.json 文件

{
   // 定义 VSCode 的显示语言。

   "locale":"en"  ；
}

4、将en改成zh-CN重启后就变成中文

***

### 安装keil插件

同样的，在插件那里查找Keil Assistant

![keil插件](https://img-blog.csdnimg.cn/20201122183739896.png#pic_center)

C/C++ IntelliSense（PS：这个插件安装好就不用管它了，要问问什么，因为没啥可管的）

![rMX66f.md.png](https://s3.ax1x.com/2020/12/15/rMX66f.md.png)

***

### keil assistant的设置和使用

打开Keil Assiatant的扩展设置，填写UV4.exe的路径到对应位置即可。这里用的是Keil C51，如果是Keil MDK，就填写在下面。

![rMvnIJ.md.png](https://s3.ax1x.com/2020/12/15/rMvnIJ.md.png)

然后就可以添加Keil工程到VS Code了：

![rMxPTe.md.png](https://s3.ax1x.com/2020/12/15/rMxPTe.md.png)

点击这里进行编译，或者按F7编译：

![rMxum8.png](https://s3.ax1x.com/2020/12/15/rMxum8.png)

***

但是注意，VSCode只是一个纯文本**编辑器**(editor)，不是IDE(集成开发环境)，不含**编译器**(compiler)和许多其它功能，所以需要自己先搭建环境。但是对很多刚上手或者初次使用的朋友来说，面对一堆的环境变量操作，搭建环境就成了一个麻烦事，动辄就要十几分钟甚至几十分钟。

***

我遇到的问题主要是配置c语言环境时MinGw必需文件下载不下来（f**k the wall）

![rFW7vj.md.png](https://s3.ax1x.com/2020/12/10/rFW7vj.md.png)

于是乎，去网上找了另一条途径，这个大佬做成了视频参考如下

<iframe id="b" class="b video_pc" src="https://xbeibeix.com/api/bilibili/biliplayer/?url=https://www.bilibili.com/video/av52434248" 
frameborder="0"
framespacing="0"
allowfullscreen="true"
style="position: middle;
width="80%" 
height="500" 
controls="controls" 
autoplay="autoplay"
quality="high">
</video>>
</iframe>

就是这个版本较老了，新的方法还在找。

分割线***

***

新的方法找到了

MinGW64 链接：https://pan.baidu.com/s/12WgeDh6MrnOI9SwPBF7IzA 
提取码：bh7u

网上有一些朋友分享了MinGW64的文件，直接下载下来放到一些地方别再动就可以了。

### **使用教程**

配置一下系统变量即可，具体教程可以去网上寻找一下，在此不再赘述（水平不足）。