---
layout: post
title: "Enhancing SDO/HMI images using deep learning"
date: 2018-01-30 19:45:05
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: C.J. Diaz Baso, A. Asensio Ramos
mathjax: true
---

* content
{:toc}

##### Abstract
The Helioseismic and Magnetic Imager (HMI) provides continuum images and magnetograms with a cadence better than one per minute. It has been continuously observing the Sun 24 hours a day for the past 7 years. The obvious trade-off between full disk observations and spatial resolution makes HMI not enough to analyze the smallest-scale events in the solar atmosphere. Our aim is to develop a new method to enhance HMI data, simultaneously deconvolving and super-resolving images and magnetograms. The resulting images will mimic observations with a diffraction-limited telescope twice the diameter of HMI. Our method, which we call Enhance, is based on two deep fully convolutional neural networks that input patches of HMI observations and output deconvolved and super-resolved data. The neural networks are trained on synthetic data obtained from simulations of the emergence of solar active regions. We have obtained deconvolved and supper-resolved HMI images. To solve this ill-defined problem with infinite solutions we have used a neural network approach to add prior information from the simulations. We test Enhance against Hinode data that has been degraded to a 28 cm diameter telescope showing very good consistency. The code is open source.

##### Abstract (translated by Google)
Helioseismic和磁性成像仪（HMI）提供的连续图像和磁图的节奏优于每分钟一次。过去7年来一直在24小时不间断的观察太阳。全盘观测和空间分辨率之间明显的折衷使人机界面不足以分析太阳大气中最小规模的事件。我们的目标是开发一种增强HMI数据的新方法，同时对图像和磁图进行去卷积和超分辨。由此产生的图像将模拟HMI的直径两倍的衍射极限望远镜的观测。我们称之为增强（Enhance）的方法是基于两个深度完全卷积神经网络，它们输入人机界面（HMI）观测点并输出解卷积和超分辨数据。神经网络是通过模拟太阳活动区域出现的合成数据进行训练的。我们已经获得了解卷和超解析的HMI图像。为了用无限的解决方案来解决这个不明确的问题，我们使用神经网络方法来添加模拟中的先验信息。我们测试Enhance对抗Hinode数据，这些数据已经退化为28厘米直径的望远镜，显示出非常好的一致性。该代码是开源的。

##### URL
[http://arxiv.org/abs/1706.02933](http://arxiv.org/abs/1706.02933)

##### PDF
[http://arxiv.org/pdf/1706.02933](http://arxiv.org/pdf/1706.02933)

