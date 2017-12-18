---
layout: post
title: "Image-Image Domain Adaptation with Preserved Self-Similarity and Domain-Dissimilarity for Person Re-identification"
date: 2017-11-19 15:05:17
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial GAN Person_Re-identification
author: Weijian Deng, Liang Zheng, Guoliang Kang, Yi Yang, Qixiang Ye, Jianbin Jiao
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-ID) models trained on one domain often fail to generalize well to another. In our attempt, we present a "learning via translation" framework. In the baseline, we translate the labeled images from source to target domain in an unsupervised manner. We then train re-ID models with the translated images by supervised methods. Yet, being an essential part of this framework, unsupervised image-image translation suffers from the information loss of source-domain labels during translation. Our motivation is two-fold. First, for each image, the discriminative cues contained in its ID label should be maintained after translation. Second, given the fact that two domains have entirely different persons, a translated image should be dissimilar to any of the target IDs. To this end, we propose to preserve two types of unsupervised similarities, 1) self-similarity of an image before and after translation, and 2) domain-dissimilarity of a translated source image and a target image. Both constraints are implemented in the similarity preserving generative adversarial network (SPGAN) which consists of a Siamese network and a CycleGAN. Through domain adaptation experiment, we show that images generated by SPGAN are more suitable for domain adaptation and yield consistent and competitive re-ID accuracy on two large-scale datasets.

##### Abstract (translated by Google)
在一个域上训练的人重新识别（re-ID）模型通常不能很好地概括到另一个域。在我们的尝试中，我们提出了一个“通过翻译学习”的框架。在基线中，我们以无监督的方式将标记的图像从源域转换为目标域。然后，我们通过监督的方法对翻译后的图像进行训练。然而，作为这一框架的重要组成部分，无监督图像翻译在翻译过程中遭受源域标签的信息丢失。我们的动机是双重的。首先，对于每幅图像，其标识标签中包含的区分线索应在翻译之后保留。其次，考虑到两个领域完全不同的人的事实，翻译的图像应该不同于任何目标ID。为此，我们建议保留两种类型的无监督相似性，1）翻译前后的图像的自相似性，以及2）翻译后的源图像和目标图像的域不相似性。这两个约束条件都是在由连体网络和CycleGAN组成的相似性保持生成对抗网络（SPGAN）中实现的。通过域适应实验，我们发现由SPGAN产生的图像更适合于域适应，并且在两个大规模数据集上产生一致且有竞争力的重定向精度。

##### URL
[https://arxiv.org/abs/1711.07027](https://arxiv.org/abs/1711.07027)

##### PDF
[https://arxiv.org/pdf/1711.07027](https://arxiv.org/pdf/1711.07027)
