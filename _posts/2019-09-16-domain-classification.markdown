---
title: "DICTA 2019 - Generalised Zero-Shot Learning with Domain Classification in a Joint Semantic and Visual Space"
layout: post
date: 2019-09-16 10:00
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

# Generalised Zero-Shot Learning with Domain Classification in a Joint Semantic and Visual Space

[Rafael Felix](http://rafafelix.com), [Ben Harwood](),[Michele Sasdelli](https://www.roboticvision.org/rv_person/michele-sasdelli/),  [Gustavo Carneiro](https://cs.adelaide.edu.au/~carneiro/)

Correspondent author: 
Rafael Felix  -- rafael dot felixalves at adelaide dot edu dot au

## Abstract

In generalized zero shot learning (GZSL), the set of classes are split into seen and unseen classes, where training relies on the semantic features of the seen and unseen classes and the visual representations of only the seen classes, while testing uses the visual representations of the seen and unseen classes. Current methods address GZSL by learning a transformation from the visual to the semantic space, exploring the assumption that the distribution of classes in the semantic and visual spaces is relatively similar. Such methods tend to transform unseen testing visual representations into one of the seen classes' semantic features instead of the semantic features of the correct unseen class, resulting in low accuracy GZSL classification. Recently, generative adversarial networks (GAN) have been explored to synthesize visual representations of the unseen classes from their semantic features - the synthesized representations of the seen and unseen classes are then used to train the GZSL classifier. This approach has been shown to boost GZSL classification accuracy, however, there is no guarantee that synthetic visual representations can generate back their semantic feature in a multi-modal cycle-consistent manner. This constraint can result in synthetic visual representations that do not represent well their semantic features. In this paper, we propose the use of such constraint based on a new regularization for the GAN training that forces the generated visual features to reconstruct their original semantic features. Once our model is trained with this multi-modal cycle-consistent semantic compatibility, we can then synthesize more representative visual representations for the seen and, more importantly, for the unseen classes. Our proposed approach shows the best GZSL classification results in the field in several publicly available datasets.

## Extra material

[pdf](https://arxiv.org/abs/1908.04930) 
|
[github](https://github.com/rfelixmg/domain-classification) 

Cite:
```
@inproceedings{felix2019domain,
  title={Multi-modal Cycle-consistent Generalized Zero-Shot Learning},
  author={Felix, Rafael and Harwood, Ben and Sasdelli, Michele and Carneiro, Gustavo},
  booktitle={Proceedings of the International Conference on Digital Image Computing: Techniques and Applications (DICTA)},
  year={2019}
}
```
