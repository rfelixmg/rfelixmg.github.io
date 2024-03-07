---
title: "WACV23 - Instance-dependent noisy label learning via graphical modelling"
layout: post
date: 2023-01-31 10:00
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

# Instance-dependent noisy label learning via graphical modelling

Arpit Garg, Cuong Nguyen, Rafael Felix, Thanh-Toan Do, Gustavo Carneiro


## Abstract

Noisy labels are unavoidable yet troublesome in the ecosystem of deep learning because models can easily overfit them. There are many types of label noise, such as symmetric, asymmetric and instance-dependent noise (IDN), with IDN being the only type that depends on image information. Such dependence on image information makes IDN a critical type of label noise to study, given that labelling mistakes are caused in large part by insufficient or ambiguous information about the visual classes present in images. Aiming to provide an effective technique to address IDN, we present a new graphical modelling approach called InstanceGM, that combines discriminative and generative models. The main contributions of InstanceGM are: i) the use of the continuous Bernoulli distribution to train the generative model, offering significant training advantages, and ii) the exploration of a state-of-the-art noisy-label discriminative classifier to generate clean labels from instance-dependent noisy-label samples. InstanceGM is competitive with current noisy-label learning approaches, particularly in instance-dependent noise benchmarks using synthetic and real-world datasets, where our method shows better accuracy than the competitors in most experiments.


## Extra material

[pdf](https://openaccess.thecvf.com/content/WACV2023/papers/Garg_Instance-Dependent_Noisy_Label_Learning_via_Graphical_Modelling_WACV_2023_paper.pdf) 
|
[github]() 

Cite:
```
@inproceedings{garg2023instance,
  title={Instance-dependent noisy label learning via graphical modelling},
  author={Garg, Arpit and Nguyen, Cuong and Felix, Rafael and Do, Thanh-Toan and Carneiro, Gustavo},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={2288--2298},
  year={2023}
}
```
