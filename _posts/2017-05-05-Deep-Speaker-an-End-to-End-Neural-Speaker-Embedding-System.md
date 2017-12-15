---
layout: post
title: "Deep Speaker: an End-to-End Neural Speaker Embedding System"
date: 2017-05-05 17:10:16
categories: arXiv_CL
tags: arXiv_CL Embedding Recognition
author: Chao Li, Xiaokong Ma, Bing Jiang, Xiangang Li, Xuewei Zhang, Xiao Liu, Ying Cao, Ajay Kannan, Zhenyao Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
We present Deep Speaker, a neural speaker embedding system that maps utterances to a hypersphere where speaker similarity is measured by cosine similarity. The embeddings generated by Deep Speaker can be used for many tasks, including speaker identification, verification, and clustering. We experiment with ResCNN and GRU architectures to extract the acoustic features, then mean pool to produce utterance-level speaker embeddings, and train using triplet loss based on cosine similarity. Experiments on three distinct datasets suggest that Deep Speaker outperforms a DNN-based i-vector baseline. For example, Deep Speaker reduces the verification equal error rate by 50% (relatively) and improves the identification accuracy by 60% (relatively) on a text-independent dataset. We also present results that suggest adapting from a model trained with Mandarin can improve accuracy for English speaker recognition.

##### Abstract (translated by Google)
我们提出了Deep Speaker，这是一个神经说话人嵌入系统，它将话语映射到一个超球面，说话人的相似度是用余弦相似度来度量的。 Deep Speaker生成的嵌入可用于许多任务，包括说话人识别，验证和聚类。我们尝试用ResCNN和GRU体系结构来提取声学特征，然后利用均值池来产生话语级别的说话人嵌入，并且使用基于余弦相似性的三重信号丢失训练。在三个不同的数据集上的实验表明，Deep Speaker胜过了基于DNN的i矢量基线。例如，Deep Speaker将验证相等的错误率降低了50％（相对），并且在独立于文本的数据集上将识别精度提高了60％（相对）。我们还提出了一些结果，表明从用普通话训练的模型进行适应可以提高英语说话人识别的准确性。

##### URL
[https://arxiv.org/abs/1705.02304](https://arxiv.org/abs/1705.02304)

##### PDF
[https://arxiv.org/pdf/1705.02304](https://arxiv.org/pdf/1705.02304)
