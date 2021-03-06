---
layout: post
title: "Computationally efficient cardiac views projection using 3D Convolutional Neural Networks"
date: 2017-11-03 21:47:05
categories: arXiv_CV
tags: arXiv_CV CNN
author: Matthieu Le, Jesse Lieman-Sifry, Felix Lau, Sean Sall, Albert Hsiao, Daniel Golden
mathjax: true
---

* content
{:toc}

##### Abstract
4D Flow is an MRI sequence which allows acquisition of 3D images of the heart. The data is typically acquired volumetrically, so it must be reformatted to generate cardiac long axis and short axis views for diagnostic interpretation. These views may be generated by placing 6 landmarks: the left and right ventricle apex, and the aortic, mitral, pulmonary, and tricuspid valves. In this paper, we propose an automatic method to localize landmarks in order to compute the cardiac views. Our approach consists of first calculating a bounding box that tightly crops the heart, followed by a landmark localization step within this bounded region. Both steps are based on a 3D extension of the recently introduced ENet. We demonstrate that the long and short axis projections computed with our automated method are of equivalent quality to projections created with landmarks placed by an experienced cardiac radiologist, based on a blinded test administered to a different cardiac radiologist.

##### Abstract (translated by Google)
4D Flow是一个MRI序列，可以采集心脏的3D图像。数据通常是按体积采集的，因此必须重新格式化以产生心脏长轴和短轴视图以进行诊断解释。这些视图可以通过放置6个标志点产生：左心室和右心室尖端以及主动脉瓣，二尖瓣，肺和三尖瓣。在本文中，我们提出了一种自动方法来定位地标，以计算心脏的意见。我们的方法是首先计算一个边界框，紧紧地裁剪心脏，然后在这个有界区域内进行地标定位。这两个步骤都基于最近推出的ENet的3D扩展。我们证明，使用我们的自动化方法计算出的长轴和短轴投影与基于对不同心脏放射科医师进行盲法检测的有经验的心脏放射科医师放置的地标创建的投影具有同等的质量。

##### URL
[https://arxiv.org/abs/1711.01345](https://arxiv.org/abs/1711.01345)

##### PDF
[https://arxiv.org/pdf/1711.01345](https://arxiv.org/pdf/1711.01345)

