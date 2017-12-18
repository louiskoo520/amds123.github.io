---
layout: post
title: "Are You Talking to Me? Reasoned Visual Dialog Generation through Adversarial Learning"
date: 2017-11-21 03:11:49
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Reinforcement_Learning VQA
author: Qi Wu, Peng Wang, Chunhua Shen, Ian Reid, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
The Visual Dialogue task requires an agent to engage in a conversation about an image with a human. It represents an extension of the Visual Question Answering task in that the agent needs to answer a question about an image, but it needs to do so in light of the previous dialogue that has taken place. The key challenge in Visual Dialogue is thus maintaining a consistent, and natural dialogue while continuing to answer questions correctly. We present a novel approach that combines Reinforcement Learning and Generative Adversarial Networks (GANs) to generate more human-like responses to questions. The GAN helps overcome the relative paucity of training data, and the tendency of the typical MLE-based approach to generate overly terse answers. Critically, the GAN is tightly integrated into the attention mechanism that generates human-interpretable reasons for each answer. This means that the discriminative model of the GAN has the task of assessing whether a candidate answer is generated by a human or not, given the provided reason. This is significant because it drives the generative model to produce high quality answers that are well supported by the associated reasoning. The method also generates the state-of-the-art results on the primary benchmark.

##### Abstract (translated by Google)
视觉对话任务要求代理人与人进行关于图像的对话。它代表了视觉问题回答任务的延伸，因为代理人需要回答关于图像的问题，但是需要根据之前的对话进行。因此，视觉对话中的关键挑战是保持一致的自然对话，同时继续正确回答问题。我们提出了一种结合强化学习和生成敌对网络（GAN）的新颖方法，以产生更多类似于人类的问题回答。 GAN有助于克服训练数据的相对不足，以及典型的基于MLE的方法产生过于简洁的答案的趋势。关键的是，GAN被紧密地整合到注意机制中，为每个答案产生人类可解释的原因。这意味着GAN的判别模型具有评估候选答案是否由人类产生的任务，并给出了提供的原因。这是非常重要的，因为它驱使生成模型产生高质量的答案，并且得到相关推理的支持。该方法还生成主要基准测试中的最新结果。

##### URL
[https://arxiv.org/abs/1711.07613](https://arxiv.org/abs/1711.07613)

##### PDF
[https://arxiv.org/pdf/1711.07613](https://arxiv.org/pdf/1711.07613)
