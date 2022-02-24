---
layout: post
comments: true
title: "Visual Attention Network"
date: 2022-02-24 17:00:00
tags: Attention
image: "data_size_vs_model_performance.png"
---

> Starting earlier this year, I grew a strong curiosity of deep learning and spent some time reading about this field. To document what I’ve learned and to provide some interesting pointers to people with similar interests, I wrote this overview of deep learning models and their applications.


<!--more-->



* TOC
{:toc}
# 视觉注意力



---

I believe many of you have watched or heard of the [games](https://youtu.be/vFr3K2DORc8) between AlphaGo and professional Go player [Lee Sedol](https://en.wikipedia.org/wiki/Lee_Sedol) in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he [lost by 1-4](https://www.scientificamerican.com/article/how-the-computer-beat-the-go-master/) in this series versus AlphaGo. Before this, Go was considered to be an intractable game for computers to master, as its simple rules lay out an exponential number of variations in the board positions, many more than what in Chess. This event surely highlighted 2016 as a big year for AI. Because of AlphaGo, much attention has been attracted to the progress of AI.


Meanwhile, many companies are spending resources on pushing the edges of AI applications, that indeed have the potential to change or even revolutionize how we are gonna live. Familiar examples include self-driving cars, chatbots, home assistant devices and many others. One of the secret receipts behind the progress we have had in recent years is deep learning.



[10] Goodfellow, Ian, et al. ["Generative adversarial nets."](https://arxiv.org/pdf/1406.2661.pdf) NIPS, 2014.

---

*If you notice mistakes and errors in this post, don't hesitate to contact me at [lilian dot wengweng at gmail dot com] and I would be super happy to correct them right away!*
