---
layout: post
title: "On Clustering and Embedding Mixture Manifolds using a Low Rank Neighborhood Approach"
date: 2017-08-12 19:28:38
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Arun M. Saranathan, Mario Parente
mathjax: true
---

* content
{:toc}

##### Abstract
Samples from intimate (non-linear) mixtures are generally modeled as being drawn from a smooth manifold. Scenarios where the data contains multiple intimate mixtures with some constituent materials in common can be thought of as manifolds which share a boundary. Two important steps in the processing of such data are (i) to identify (cluster) the different mixture-manifolds present in the data and (ii) to eliminate the non-linearities present the data by mapping each mixture-manifold into some low-dimensional euclidean space (embedding). Manifold clustering and embedding techniques appear to be an ideal tool for this task, but the present state-of-the-art algorithms perform poorly for hyperspectral data, particularly in the embedding task. We propose a novel reconstruction-based algorithm for improved clustering and embedding of mixture-manifolds. The algorithms attempts to reconstruct each target-point as an affine combination of its nearest neighbors with an additional rank penalty on the neighborhood to ensure that only neighbors on the same manifold as the target-point are used in the reconstruction. The reconstruction matrix generated by using this technique is block-diagonal and can be used for clustering (using spectral clustering) and embedding. The improved performance of the algorithms vis-a-vis its competitors is exhibited on a variety of simulated and real mixture datasets.

##### Abstract (translated by Google)
通常将来自紧密（非线性）混合物的样品建模为从光滑歧管中抽取。数据中包含多个密切混合的情况，其中一些组成材料是共同的，可以被认为是共享边界的流形。处理这些数据的两个重要步骤是：（i）识别（聚类）数据中存在的不同混合物流形;（ii）通过将每个混合物 - 流形映射到一些低分辨率数据中来消除呈现数据的非线性，三维欧氏空间（嵌入）。流形聚类和嵌入技术似乎是这项任务的理想工具，但目前最先进的算法对于高光谱数据表现不佳，特别是在嵌入任务中。我们提出了一种新的基于重构的混合流形的聚类和嵌入算法。这些算法试图将每个目标点重建为其最近邻居的仿射组合，并且在邻域上具有额外的等级惩罚，以确保在重建中仅使用与目标点相同的流形上的邻居。使用这种技术生成的重建矩阵是块对角线，可用于聚类（使用谱聚类）和嵌入。该算法相对于其竞争对手的改进性能在各种模拟和真实的混合数据集上展示。

##### URL
[https://arxiv.org/abs/1608.06669](https://arxiv.org/abs/1608.06669)

##### PDF
[https://arxiv.org/pdf/1608.06669](https://arxiv.org/pdf/1608.06669)
