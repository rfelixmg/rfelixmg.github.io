---
title: "SUBM22 - Noisy-label Learning with Sample Selection based on Noise Rate Estimate"
layout: post
date: 2022-01-01 10:00
image: /assets/images/markdown.jpg
headerImage: false
tag:
- markdown
- components
- extra
category: publications
author: rfelixmg
# jemoji: '<img class="emoji" title=":ramen:" alt=":ramen:" src="https://assets.github.com/images/icons/emoji/unicode/1f35c.png" height="20" width="20" align="absmiddle">'
---

# Noisy-label Learning with Sample Selection based on Noise Rate Estimate

A Garg, C Nguyen, R Felix, TT Do, G Carneiro

## Abstract

Noisy-labels are challenging for deep learning due to the high capacity of the deep models that can overfit noisy-label training samples. Arguably the most realistic and coincidentally challenging type of label noise is the instance-dependent noise (IDN), where the labelling errors are caused by the ambivalent information present in the images. The most successful label noise learning techniques to address IDN problems usually contain a noisy-label sample selection stage to separate clean and noisy-label samples during training. Such sample selection depends on a criterion, such as loss or gradient, and on a curriculum to define the proportion of training samples to be classified as clean at each training epoch. Even though the estimated noise rate from the training set appears to be a natural signal to be used in the definition of this curriculum, previous approaches generally rely on arbitrary thresholds or pre-defined selection functions to the best of our knowledge. This paper addresses this research gap by proposing a new noisy-label learning graphical model that can easily accommodate state-of-the-art (SOTA) noisy-label learning methods and provide them with a reliable noise rate estimate to be used in a new sample selection curriculum. We show empirically that our model integrated with many SOTA methods can improve their results in many IDN benchmarks, including synthetic and real-world datasets.


## Extra material

[pdf](https://arxiv.org/pdf/2305.19486.pdf) 
|
[github]() 

Cite:
```
@article{garg2023noisy,
  title={Noisy-label Learning with Sample Selection based on Noise Rate Estimate},
  author={Garg, Arpit and Nguyen, Cuong and Felix, Rafael and Do, Thanh-Toan and Carneiro, Gustavo},
  journal={arXiv preprint arXiv:2305.19486},
  year={2023}
}
```
