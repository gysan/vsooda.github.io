---
layout: post
title:  "2015年度总结"
date:   2016-01-03
categories:  life
tags: summary run
---
* content
{:toc}

2015年的年度关键词：工作。其他的基本什么都没发生。曾经连续加班50天。脖子有点问题了。今年要更加注重锻炼了。



2015年涉及的领域最广：除了一直在做的图像之外，还涉及了3D， ios开发， 大数据，nlp， 深度学习， 语音。

使用的语言最多， 除了c++之外，还用了oc， lua， java， perl， python等（shader，scala没实际写过代码，不算在内）

从头到尾完整啃完大部头有：深入理解计算机系统，MIT的线性代数，prml只啃了部分，收获颇多，2016啃完。

### 图像
上线了人脸检测，特征点识别算法，从数据标定到最终上线。上线了光照均衡，磨皮。实现了特征点模型压缩，在手机上实行运行。实现了眼睛精确定位。

### 3D
1月份的时候利用业余时间看了以下3D，对于渲染流程有一些认识，对于设计的数学计算也有大概的了解。接触了shader

### ios开发
开发ios上的实时姿态检测。由于项目用到的ios开发，是封装view再使用lua调用。所以对ios本身的开发并不算很了解。不过，系统分析了lua的mvc框架kode，对于使用lua从头构建面向对象系统，构建消息处理系统有一定认识；分析了跨语音swig。熟悉语言：oc， lua

### 大数据
6月底用了两周时间调研了大数据方案，spark，hadoop， kafka等，了解一下scala。

### nlp
目标是做情感分析，自动对话系统。用python实现基于关键词匹配的情感计算，已经自动回复。后来转向rnn

### 深度学习
系统看了ng的网页教程。推导了rnn， lstm，bptt等。个人比较熟悉Andrej Karpathy。分析neuraltalk源码，glove源码。caffe，torch，keras，mxnet都跑过一些代码。用keras写了seq2seq。其他的没有实际写过代码。

### 语音
主要是语音合成，未来可能研究语音识别。从0开始构建语音合成系统。phoneset，对齐，hmm，合成。主要用到语音包，htk/hts。改进方向，使用rnn来替换gmm。外围流程已经解决差不多了。2016更多的要解决：htk/hts内部问题，vocoder问题，特征问题。2015的最后一天htk3.5发布，支持rnn，支持cuda。可以解决训练速度问题？另外关注一下kaldi。

这个过程使用的语音：java， perl。并用maven管理项目包。


## 2016年计划
2015涉及的东西真是相当多。除非计划有变，2016将集中在语音领域，将htk，hts，kaldi吃透。研究speech算法，研究cuda源码，研究分布式方案，研究mxnet。啃大部头。又将是忙碌的一年。

注意锻炼身体，注意休息。除了工作别忽略沿途风景。
