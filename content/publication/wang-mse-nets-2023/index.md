---
title: 'MSE-Nets: Multi-annotated Semi-supervised Ensemble Networks for Improving
  Segmentation of Medical Image with Ambiguous Boundaries'
authors:
- Shuai Wang
- Tengjin Weng
- Jingyi Wang
- Yang Shen
- Zhidong Zhao
- Yixiu Liu
- Pengfei Jiao
- Zhiming Cheng
- Yaqi Wang
date: '2023-11-01'
publishDate: '2024-03-07T06:17:41.700690Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2311.10380
abstract: 'Medical image segmentation annotations exhibit variations among experts
  due to the ambiguous boundaries of segmented objects and backgrounds in medical
  images. Although using multiple annotations for each image in the fully-supervised
  has been extensively studied for training deep models, obtaining a large amount
  of multi-annotated data is challenging due to the substantial time and manpower
  costs required for segmentation annotations, resulting in most images lacking any
  annotations. To address this, we propose Multi-annotated Semi-supervised Ensemble
  Networks (MSE-Nets) for learning segmentation from limited multi-annotated and abundant
  unannotated data. Specifically, we introduce the Network Pairwise Consistency Enhancement
  (NPCE) module and Multi-Network Pseudo Supervised (MNPS) module to enhance MSE-Nets
  for the segmentation task by considering two major factors: (1) to optimize the
  utilization of all accessible multi-annotated data, the NPCE separates (dis)agreement
  annotations of multi-annotated data at the pixel level and handles agreement and
  disagreement annotations in different ways, (2) to mitigate the introduction of
  imprecise pseudo-labels, the MNPS extends the training data by leveraging consistent
  pseudo-labels from unannotated data. Finally, we improve confidence calibration
  by averaging the predictions of base networks. Experiments on the ISIC dataset show
  that we reduced the demand for multi-annotated data by 97.75% and narrowed the gap
  with the best fully-supervised baseline to just a Jaccard index of 4%. Furthermore,
  compared to other semi-supervised methods that rely only on a single annotation
  or a combined fusion approach, the comprehensive experimental results on ISIC and
  RIGA datasets demonstrate the superior performance of our proposed method in medical
  image segmentation with ambiguous boundaries.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: PDF
  url: https://github.com/cspjiao/cspjiao.github.io/blob/main/content/publication/chen-enhancing-2023/Chen%20et%20al_2023_Enhancing%20Network%20Alignment%20through%20Multi-Scale%20Information%20Fusion.pdf
- name: Code
  url: ''
---
