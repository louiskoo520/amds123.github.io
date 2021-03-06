---
layout: post
title: "Learning a Deep Embedding Model for Zero-Shot Learning"
date: 2017-04-12 10:30:48
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Embedding
author: Li Zhang, Tao Xiang, Shaogang Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) models rely on learning a joint embedding space where both textual/semantic description of object classes and visual representation of object images can be projected to for nearest neighbour search. Despite the success of deep neural networks that learn an end-to-end model between text and images in other vision problems such as image captioning, very few deep ZSL model exists and they show little advantage over ZSL models that utilise deep feature representations but do not learn an end-to-end embedding. In this paper we argue that the key to make deep ZSL models succeed is to choose the right embedding space. Instead of embedding into a semantic space or an intermediate space, we propose to use the visual space as the embedding space. This is because that in this space, the subsequent nearest neighbour search would suffer much less from the hubness problem and thus become more effective. This model design also provides a natural mechanism for multiple semantic modalities (e.g., attributes and sentence descriptions) to be fused and optimised jointly in an end-to-end manner. Extensive experiments on four benchmarks show that our model significantly outperforms the existing models.

##### Abstract (translated by Google)
零点学习（ZSL）模型依赖于学习联合嵌入空间，其中对象类别的文本/语义描述和对象图像的视觉表示可以被投影到最近的邻居搜索。尽管在图像字幕等其他视觉问题中学习了文本和图像之间的端对端模型的深度神经网络的成功，但是很少有深度的ZSL模型存在，并且与使用深度特征表示的ZSL模型相比，它们几乎没有什么优势不学习端到端的嵌入。在本文中，我们认为使ZSL模型成功的关键在于选择合适的嵌入空间。我们建议将视觉空间作为嵌入空间，而不是嵌入到语义空间或中间空间中。这是因为在这个空间中，随后的最近邻搜索会受到中枢问题的影响要小得多，从而变得更加有效。该模型设计还为多个语义模态（例如，属性和句子描述）提供了以端到端方式联合融合和优化的自然机制。四个基准的大量实验表明，我们的模型显着优于现有的模型。

##### URL
[https://arxiv.org/abs/1611.05088](https://arxiv.org/abs/1611.05088)

##### PDF
[https://arxiv.org/pdf/1611.05088](https://arxiv.org/pdf/1611.05088)

