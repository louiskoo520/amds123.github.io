---
layout: post
title: "Incremental 3D Line Segments Extraction from Semi-dense SLAM"
date: 2017-10-25 19:03:21
categories: arXiv_CV
tags: arXiv_CV Face SLAM
author: Shida He, Xuebin Qin, Zichen Zhang, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
Despite much interest in Simultaneous Localization and Mapping (SLAM), there is a lack of efficient methods for representing and processing their large scale point clouds. In this paper, we propose to simplify the point clouds generated by the semi-dense SLAM using three-dimensional (3D) line segments. Specifically, we present a novel incremental approach for 3D line segments extraction. This approach reduces a 3D line segment fitting problem into two two-dimensional (2D) line segment fitting problems, which take advantage of both image edge segments and depth maps. We first detect edge segments, which are one-pixel-width pixel chains from keyframes. We then search 3D line segments of each keyframe along their detected edge pixel chains by minimizing the fitting error on both image plane and depth plane. By incrementally clustering the detected line segments, we show that the resulting 3D representation for the scene achieves a good balance between compactness and completeness. Our experimental results show that the 3D line segments generated by our method are highly accurate in terms of the location of their end points. Additionally, we also demonstrate that these line segments greatly improve the quality of 3D surface reconstruction compared to a feature point based baseline.

##### Abstract (translated by Google)
尽管对同时定位和映射（SLAM）非常感兴趣，但是缺乏用于表示和处理它们的大规模点云的有效方法。在本文中，我们建议使用三维（3D）线段来简化半密集SLAM产生的点云。具体来说，我们提出了一种新颖的三维线段提取的增量方法。这种方法将3D线段拟合问题减少为两个二维（2D）线段拟合问题，其利用了图像边缘段和深度图。我们首先检测边缘片段，这些边缘片段是来自关键帧的一个像素宽度的像素链。然后，我们通过最小化图像平面和深度平面上的拟合误差，沿着它们的检测到的边缘像素链搜索每个关键帧的3D线段。通过对检测到的线段进行递增聚类，我们可以看出，场景的三维表示在紧凑性和完整性之间取得了很好的平衡。我们的实验结果表明，我们的方法生成的三维线段在其端点的位置方面是高度准确的。此外，我们还证明，与基于特征点的基线相比，这些线段极大地提高了三维表面重建的质量。

##### URL
[https://arxiv.org/abs/1708.03275](https://arxiv.org/abs/1708.03275)

##### PDF
[https://arxiv.org/pdf/1708.03275](https://arxiv.org/pdf/1708.03275)

