---
layout: post
title: "RED-Net: A Recurrent Encoder-Decoder Network for Video-based Face Alignment"
date: 2018-01-17 04:29:44
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Xi Peng, Rogerio S. Feris, Xiaoyu Wang, Dimitris N. Metaxas
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for real-time face alignment in videos based on a recurrent encoder-decoder network model. Our proposed model predicts 2D facial point heat maps regularized by both detection and regression loss, while uniquely exploiting recurrent learning at both spatial and temporal dimensions. At the spatial level, we add a feedback loop connection between the combined output response map and the input, in order to enable iterative coarse-to-fine face alignment using a single network model, instead of relying on traditional cascaded model ensembles. At the temporal level, we first decouple the features in the bottleneck of the network into temporal-variant factors, such as pose and expression, and temporal-invariant factors, such as identity information. Temporal recurrent learning is then applied to the decoupled temporal-variant features. We show that such feature disentangling yields better generalization and significantly more accurate results at test time. We perform a comprehensive experimental analysis, showing the importance of each component of our proposed model, as well as superior results over the state of the art and several variations of our method in standard datasets.

##### Abstract (translated by Google)
我们提出了一种基于循环编解码器网络模型的视频实时人脸对齐方法。我们提出的模型预测二维面部点热图既检测和回归损失规律化，而独特地利用循环学习在空间和时间维度。在空间层次上，我们在组合的输出响应图和输入之间增加一个反馈回路连接，以便使用单一网络模型来实现迭代的从粗到精的人脸对齐，而不是依靠传统的级联模型集合。在时间层面上，我们首先将网络瓶颈中的特征分解为姿态和表达等时变因素以及身份信息等时态不变因素。然后将时间递归学习应用于解耦的时间变量特征。我们表明，这样的功能解开产生更好的泛化和在测试时间显着更准确的结果。我们进行了全面的实验分析，显示了我们提出的模型的每个组成部分的重要性，以及优于现有技术和我们的方法在标准数据集中的多种变化的结果。

##### URL
[http://arxiv.org/abs/1801.06066](http://arxiv.org/abs/1801.06066)

##### PDF
[http://arxiv.org/pdf/1801.06066](http://arxiv.org/pdf/1801.06066)

