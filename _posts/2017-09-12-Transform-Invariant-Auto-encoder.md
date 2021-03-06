---
layout: post
title: "Transform Invariant Auto-encoder"
date: 2017-09-12 09:19:34
categories: arXiv_CV
tags: arXiv_CV Inference
author: Tadashi Matsuo, Hiroya Fukuhara, Nobutaka Shimada
mathjax: true
---

* content
{:toc}

##### Abstract
The auto-encoder method is a type of dimensionality reduction method. A mapping from a vector to a descriptor that represents essential information can be automatically generated from a set of vectors without any supervising information. However, an image and its spatially shifted version are encoded into different descriptors by an existing ordinary auto-encoder because each descriptor includes a spatial subpattern and its position. To generate a descriptor representing a spatial subpattern in an image, we need to normalize its spatial position in the images prior to training an ordinary auto-encoder; however, such a normalization is generally difficult for images without obvious standard positions. We propose a transform invariant auto-encoder and an inference model of transform parameters. By the proposed method, we can separate an input into a transform invariant descriptor and transform parameters. The proposed method can be applied to various auto-encoders without requiring any special modules or labeled training samples. By applying it to shift transforms, we can achieve a shift invariant auto-encoder that can extract a typical spatial subpattern independent of its relative position in a window. In addition, we can achieve a model that can infer shift parameters required to restore the input from the typical subpattern. As an example of the proposed method, we demonstrate that a descriptor generated by a shift invariant auto-encoder can represent a typical spatial subpattern. In addition, we demonstrate the imitation of a human hand by a robot hand as an example of a regression based on spatial subpatterns.

##### Abstract (translated by Google)
自动编码器方法是一种降维方法。可以从一组矢量中自动生成从矢量到表示基本信息的描述符的映射，而无需任何监督信息。然而，由于每个描述符包括空间子模式及其位置，所以图像及其空间移位版本被现有的普通自动编码器编码成不同的描述符。为了在图像中生成表示空间子模式的描述符，我们需要在训练普通的自动编码器之前对图像中的空间位置进行归一化;然而，对于没有明显标准位置的图像来说，这样的标准化通常是困难的。我们提出了变换不变自动编码器和变换参数的推理模型。通过所提出的方法，我们可以将输入分解为变换不变描述符和变换参数。所提出的方法可以应用于各种自动编码器，而不需要任何特殊模块或标记的训练样本。通过应用它来转换变换，我们可以实现一个移位不变的自动编码器，它可以提取一个典型的空间子模式，而不依赖于它在窗口中的相对位置。另外，我们可以实现一个模型，可以推断出从典型的子模式恢复输入所需的移位参数。作为所提出的方法的一个例子，我们证明由移位不变自动编码器生成的描述符可以表示典型的空间子模式。另外，我们用一个机器人手来模拟一个人的手，作为一个基于空间子模式的回归的例子。

##### URL
[https://arxiv.org/abs/1709.03754](https://arxiv.org/abs/1709.03754)

##### PDF
[https://arxiv.org/pdf/1709.03754](https://arxiv.org/pdf/1709.03754)

