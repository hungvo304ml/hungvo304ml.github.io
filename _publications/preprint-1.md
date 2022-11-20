---
title: "Student Collaboration Improves Self-Supervised Learning: Dual-Loss Adaptive Masked Autoencoder for Multiplexed Immunofluorescence Brain Images Analysis"
collection: publications
permalink: /publication/preprint-1
excerpt: Son T Ly, Bai Lin, <b>Hung Q Vo</b>, Dragan Maric, Badri Roysam, Hien V Nguyen<br/><a href="https://arxiv.org/pdf/2205.05194.pdf">[paper]</a><br/><img src='/images/publications/preprint-1.png'>
date: 2019-09-01
venue: 'arXiv preprint arXiv:2205.05194 (2022)'
---
Self-supervised learning (SSL) leverages the underlying data structure to generate supervisory signals for training deep networks. This approach offers a practical solution for learning with multiplexed immunofluorescence brain images where data are often more abundant than human expert annotations. SSL algorithms based on contrastive learning and image reconstruction have demonstrated impressive performances. Unfortunately, these methods were designed and validated mostly on natural images rather than biomedical images. A few recent works have applied SSL to analyzing cell images. However, none of these works studies SSL for multiplexed immunofluorescence brain images. These works also did not provide a clear theoretical justification for adopting a specific SSL method. Motivated by these limitations, our paper presents a self-supervised Dual-Loss Adaptive Masked Autoencoder (DAMA) algorithm developed from the information theory viewpoint. DAMA's objective function maximizes the mutual information by minimizing the conditional entropy in pixel-level reconstruction and feature-level regression. In addition, DAMA introduces a novel adaptive mask sampling strategy to maximize mutual information and effectively learn brain cell data contextual information. For the first time, we provide extensive comparisons of SSL algorithms on multiplexed immunofluorescence brain images. Our results demonstrate that DAMA is superior to other SSL approaches on cell classification and segmentation tasks. DAMA also achieves competitive accuracies on ImageNet-1k.

[Download paper here](https://arxiv.org/abs/2205.05194)
