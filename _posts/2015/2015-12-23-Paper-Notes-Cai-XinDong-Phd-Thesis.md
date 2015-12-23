---
layout: post
title: Paper notes-Cai Xindong Phd Thesis
image:
  feature: background.jpg

comments: true
share: true


category:
- Papernotes
tags:
- quantum computing
- machine learning
- academic
--- 

文献阅读笔记 蔡昕东博士论文《光量子计算及其算法实现》

4个部分
1. 多自由度量子隐形传输
2. 量子求解线性方程组
3. 量子机器学习
4. 相位弱测量

##1  基本概念和技术
量子态叠加原理和量子比特
量子纠缠和量子隐形传态
光子极化是最常用的量子比特编码自由度。
对于光子极化量子比特的操纵和测量可以采用成熟的半波片技术：对光子极化的任意幺正旋转都可以由两块四分之一波片和和一块半波片实现；对于光子极化的测量则可以使用一块四分之一玻片、一块半波片、一个极化分束器和探测器的组合实现。
光子的其他自由度有路径、轨道角动量、频率和时间等。
纠缠光子对的产生。
当激光通过某些非线性晶体时，会有一定几率发生参量下转换(SPDC)过程，一个光子劈裂成两个低频光子对。为了弥补信号光和闲频光在空间和时间上出现的差异，需要进行补偿。


##2 多自由度量子隐形传输
信息同时编码在光子的极化和轨道角动量自由度上。发展了对于光子轨道角动量的高效率操控和测量技术手段，以及多自由度的联合操纵技术，首次实现了轨道角动量的多光子纠缠。

![Scheme for quantum teleportation of the spin–orbit composite
states](/images/posts/2015/high_quantum_teleportation.jpg)