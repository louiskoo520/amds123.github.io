---
layout: post
title: "Weakly supervised learning of actions from transcripts"
date: 2017-06-19 09:25:13
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised
author: Hilde Kuehne, Alexander Richard, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for weakly supervised learning of human actions from video transcriptions. Our system is based on the idea that, given a sequence of input data and a transcript, i.e. a list of the order the actions occur in the video, it is possible to infer the actions within the video stream, and thus, learn the related action models without the need for any frame-based annotation. Starting from the transcript information at hand, we split the given data sequences uniformly based on the number of expected actions. We then learn action models for each class by maximizing the probability that the training video sequences are generated by the action models given the sequence order as defined by the transcripts. The learned model can be used to temporally segment an unseen video with or without transcript. We evaluate our approach on four distinct activity datasets, namely Hollywood Extended, MPII Cooking, Breakfast and CRIM13. We show that our system is able to align the scripted actions with the video data and that the learned models localize and classify actions competitively in comparison to models trained with full supervision, i.e. with frame level annotations, and that they outperform any current state-of-the-art approach for aligning transcripts with video data.

##### Abstract (translated by Google)
我们提出了一个从视频转录弱监督学习人类行为的方法。我们的系统是基于这样的思想：给定一系列输入数据和一个记录，即一个动作在视频中出现的顺序列表，可以推断出视频流内的动作，从而学习相关的动作模型，而不需要任何基于框架的注释。从手头的抄本信息开始，我们根据预期的行动数量来分配给定的数据序列。然后我们通过最大化训练视频序列由动作模型产生的概率来学习每个类别的动作模型，所述动作模型给出了由成绩单定义的序列顺序。学习的模型可以用来临时分割一个看不见的视频，不论是否有成绩单。我们评估我们的方法在四个不同的活动数据集，即好莱坞扩展，MPII烹饪，早餐和CRIM13。我们表明，我们的系统能够将脚本动作与视频数据对齐，并且学习模型相对于受全面监督训练的模型（即，框架级别注释）而言具有竞争力的本地化和分类行为，并且它们胜过任何当前状态最先进的方法来对齐成绩单与视频数据。

##### URL
[https://arxiv.org/abs/1610.02237](https://arxiv.org/abs/1610.02237)

##### PDF
[https://arxiv.org/pdf/1610.02237](https://arxiv.org/pdf/1610.02237)
