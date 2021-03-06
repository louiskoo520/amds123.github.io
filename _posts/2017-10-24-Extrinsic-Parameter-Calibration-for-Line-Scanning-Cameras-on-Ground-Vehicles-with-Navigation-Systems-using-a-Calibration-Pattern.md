---
layout: post
title: "Extrinsic Parameter Calibration for Line Scanning Cameras on Ground Vehicles with Navigation Systems using a Calibration Pattern"
date: 2017-10-24 00:56:14
categories: arXiv_CV
tags: arXiv_CV
author: Alexander Wendel, James Underwood
mathjax: true
---

* content
{:toc}

##### Abstract
Line scanning cameras, which capture only a single line of pixels, have been increasingly used in ground based mobile or robotic platforms. In applications where it is advantageous to directly georeference the camera data to world coordinates, an accurate estimate of the camera's 6D pose is required. This paper focuses on the common case where a mobile platform is equipped with a rigidly mounted line scanning camera, whose pose is unknown, and a navigation system providing vehicle body pose estimates. We propose a novel method that estimates the camera's pose relative to the navigation system. The approach involves imaging and manually labelling a calibration pattern with distinctly identifiable points, triangulating these points from camera and navigation system data and reprojecting them in order to compute a likelihood, which is maximised to estimate the 6D camera pose. Additionally, a Markov Chain Monte Carlo (MCMC) algorithm is used to estimate the uncertainty of the offset. Tested on two different platforms, the method was able to estimate the pose to within 0.06 m / 1.05$^{\circ}$ and 0.18 m / 2.39$^{\circ}$. We also propose several approaches to displaying and interpreting the 6D results in a human readable way.

##### Abstract (translated by Google)
线扫描相机，只捕捉一行像素，已经越来越多地使用在地面移动或机器人平台。在将相机数据直接地理参考到世界坐标是有利的应用中，需要准确估计相机的6D姿态。本文重点介绍移动平台配备姿态未知的刚性线扫描摄像机和提供车身姿态估计的导航系统的常见情况。我们提出了一种新的方法来估计相对于导航系统的相机姿态。该方法涉及用明显可识别的点对校准图案进行成像和手动标记，从照相机和导航系统数据对这些点进行三角测量并重新投影它们以计算可能性，其被最大化以估计6D相机姿态。另外，使用马尔可夫链蒙特卡罗（MCMC）算法来估计偏移的不确定性。在两个不同的平台上进行测试，该方法能够估计出姿态在0.06m / 1.05美元/平方码和0.18m / 2.39美元/立方米的范围内。我们还提出了几种以可读的方式显示和解释6D结果的方法。

##### URL
[https://arxiv.org/abs/1709.00846](https://arxiv.org/abs/1709.00846)

##### PDF
[https://arxiv.org/pdf/1709.00846](https://arxiv.org/pdf/1709.00846)

