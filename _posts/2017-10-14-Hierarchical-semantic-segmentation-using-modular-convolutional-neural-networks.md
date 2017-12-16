---
layout: post
title: "Hierarchical semantic segmentation using modular convolutional neural networks"
date: 2017-10-14 02:44:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Classification Recognition
author: Sagi Eppel
mathjax: true
---

* content
{:toc}

##### Abstract
Image recognition tasks that involve identifying parts of an object or the contents of a vessel can be viewed as a hierarchical problem, which can be solved by initial recognition of the main object, followed by recognition of its parts or contents. To achieve such modular recognition, it is necessary to use the output of one recognition method (which identifies the general object) as the input for a second method (which identifies the parts or contents). In recent years, convolutional neural networks have emerged as the dominant method for segmentation and classification of images. This work examines a method for serially connecting convolutional neural networks for semantic segmentation of materials inside transparent vessels. It applies one fully convolutional neural net to segment the image into vessel and background, and the vessel region is used as an input for a second net which recognizes the contents of the glass vessel. Transferring the segmentation map generated by the first nets to the second net was performed using the valve filter attention method that involves using different filters on different segments of the image. This modular semantic segmentation method outperforms a single step method in which both the vessel and its contents are identified using a single net. An advantage of the modular neural net is that it allows networks to be built from existing trained modules, as well the transfer and reuse of trained net modules without the need for any retraining of the assembled net.

##### Abstract (translated by Google)
涉及识别物体的部分或船只的内容的图像识别任务可被视为分层问题，其可通过对主要目标的初始识别，随后识别其部分或内容来解决。为了实现这种模块化识别，有必要使用一种识别方法（识别一般物体）的输出作为第二种方法（识别部件或内容）的输入。近年来，卷积神经网络已经成为图像分割和分类的主要手段。这项工作考察了串联卷积神经网络的方法，用于透明容器内物质的语义分割。它使用一个完全卷积神经网络将图像分割成容器和背景，并且容器区域被用作识别玻璃容器的内容物的第二网络的输入。将由第一网生成的分割图转移到第二网使用阀过滤器关注方法执行，该方法涉及在图像的不同区段上使用不同的过滤器。这种模块化的语义分割方法胜过了使用单一网络识别容器及其内容的单步方法。模块化神经网络的一个优点是，它允许从现有的训练模块构建网络，以及训练的网络模块的传输和再利用，而不需要对组装的网络进行再训练。

##### URL
[https://arxiv.org/abs/1710.05126](https://arxiv.org/abs/1710.05126)

##### PDF
[https://arxiv.org/pdf/1710.05126](https://arxiv.org/pdf/1710.05126)
