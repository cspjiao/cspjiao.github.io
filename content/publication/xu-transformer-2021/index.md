---
title: Transformer Reasoning Network for Personalized Review Summarization
authors:
- Hongyan Xu
- Hongtao Liu
- jiaopengfei_en
- Wenjun Wang
date: '2021-07-01'
publishDate: '2024-03-12T01:17:25.093221Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 44th International ACM SIGIR Conference on Research
  and Development in Information Retrieval*'
doi: 10.1145/3404835.3462854
abstract: Review summarization aims to generate condensed text for online product
  reviews, and has attracted more and more attention in E-commerce platforms. In addition
  to the input review, the quality of generated summaries is highly related to the
  characteristics of users and products, e.g., their historical summaries, which could
  provide useful clues for the target summary generation. However, most previous works
  ignore the underlying interaction between the given input review and the corresponding
  historical summaries. Therefore, we aim to explore how to effectively incorporate
  the history information into the summary generation. In this paper, we propose a
  novel transformer-based reasoning framework for personalized review summarization.
  We design an elaborately adapted transformer network containing an encoder and a
  decoder, to fully infer the important and informative parts among the historical
  summaries in terms of the input review to generate more comprehensive summaries.
  In the encoder of our approach, we develop an inter- and intra-attention to involve
  the history information selectively to learn the personalized representation of
  the input review. In the decoder part, we propose to incorporate the constructed
  reasoning memory learning from historical summaries into the original transformer
  decoder, and design a memory-decoder attention module to retrieve more useful information
  for the final summary generation. Extensive experiments are conducted and the results
  show our approach could generate more reasonable summaries for recommendation, and
  outperform many competitive baseline methods.
tags:
- personalized review summarization
- reasoning network
- recommender system
- transformer
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3404835.3462854
---
