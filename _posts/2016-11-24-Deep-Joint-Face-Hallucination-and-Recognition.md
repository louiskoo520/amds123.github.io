---
layout: post
title: "Deep Joint Face Hallucination and Recognition"
date: 2016-11-24 08:19:49
categories: arXiv_CV
tags: arXiv_CV Face Classification Recognition Face_Recognition
author: Junyu Wu, Shengyong Ding, Wei Xu, Hongyang Chao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep models have achieved impressive performance for face hallucination tasks. However, we observe that directly feeding the hallucinated facial images into recog- nition models can even degrade the recognition performance despite the much better visualization quality. In this paper, we address this problem by jointly learning a deep model for two tasks, i.e. face hallucination and recognition. In particular, we design an end-to-end deep convolution network with hallucination sub-network cascaded by recognition sub-network. The recognition sub- network are responsible for producing discriminative feature representations using the hallucinated images as inputs generated by hallucination sub-network. During training, we feed LR facial images into the network and optimize the parameters by minimizing two loss items, i.e. 1) face hallucination loss measured by the pixel wise difference between the ground truth HR images and network-generated images; and 2) verification loss which is measured by the classification error and intra-class distance. We extensively evaluate our method on LFW and YTF datasets. The experimental results show that our method can achieve recognition accuracy 97.95% on 4x down-sampled LFW testing set, outperforming the accuracy 96.35% of conventional face recognition model. And on the more challenging YTF dataset, we achieve recognition accuracy 90.65%, a margin over the recognition accuracy 89.45% obtained by conventional face recognition model on the 4x down-sampled version.

##### Abstract (translated by Google)
深度模型已经取得令人印象深刻的表面幻觉任务的表现。然而，我们观察到，尽管有更好的可视化质量，但直接将幻觉面部图像输入识别模型甚至会降低识别性能。在本文中，我们通过联合学习两个任务的深层模型来解决这个问题，即面对幻觉和识别。具体而言，我们设计了一个由识别子网络级联的幻觉子网络的端到端深度卷积网络。识别子网络负责使用由幻觉子网络产生的幻觉图像作为输入来产生识别性特征表示。在训练期间，我们将LR面部图像馈送到网络中，并通过最小化两个损失项目来优化参数，即1）通过地面实况HR图像和网络生成的图像之间的像素差异测量的面部幻觉损失;以及2）由分类错误和类内距离测量的验证损失。我们广泛地评估了我们在LFW和YTF数据集上的方法。实验结果表明，该方法在4倍下采样LFW测试集上的识别准确率达到97.95％，优于传统人脸识别模型的96.35％。在更具挑战性的YTF数据集上，我们实现了90.65％的识别准确率，比传统人脸识别模型在4x下采样版本上获得的识别准确率高89.45％。

##### URL
[https://arxiv.org/abs/1611.08091](https://arxiv.org/abs/1611.08091)

##### PDF
[https://arxiv.org/pdf/1611.08091](https://arxiv.org/pdf/1611.08091)
