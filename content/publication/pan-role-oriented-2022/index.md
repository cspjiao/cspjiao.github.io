---
title: Role-Oriented Dynamic Network Embedding
authors:
- Ting Pan
- Wenjun Wang
- Minglai Shao
- Yueheng Sun
- Pengfei Jiao
date: '2022-12-01'
publishDate: '2024-03-07T06:17:41.716056Z'
publication_types:
- paper-conference
publication: '*2022 IEEE International Conference on Big Data (Big Data)*'
doi: 10.1109/BigData55660.2022.10020276
abstract: Exploring the differences and important patterns of nodes from the perspective
  of roles has gradually developed into an interesting and important topic in network
  analysis. However, existing role-oriented network embedding methods focus more on
  identifying underlying roles for static network, which leads to complex temporal
  behaviors being overlooked and degraded performance facing dynamic network. The
  few role analytics methods for dynamic networks either cannot learn general node
  representations or fail to discovery role transitions of nodes. In this work, we
  propose a unified framework RDNE (Role-oriented Dynamic Network Embedding) to tackle
  such challenges, which aim to learn multiple embeddings for individual nodes based
  on time-varying structural behaviors. Based on regular equivalence, RDNE propagates
  the structural features over the graph to derive the initial role-oriented representations.
  Then, it applies capsule network to further model the mapping between nodes and
  roles, which is the first time capsule network is used for role discovery. For the
  varying and temporal dependence within dynamic network, we utilize the Gated Recurrent
  Unit to compute historical information and use historical information to influence
  the generation of representations at the next snapshot. Comprehensive experiments
  on both synthetic and real-world networks validate the superiority of the proposed
  RDNE.
tags:
- Big Data
- Capsule Network
- Complex networks
- Computational modeling
- Data models
- Dynamic Network Embedding
- Gated Recurrent Unit (GRU)
- Graph Convolutional Networks (GCNs)
- Logic gates
- Market research
- Network analyzers
- Role Discovery
links:
- name: PDF
  url: https://github.com/cspjiao/cspjiao.github.io/blob/main/content/publication/chen-enhancing-2023/Chen%20et%20al_2023_Enhancing%20Network%20Alignment%20through%20Multi-Scale%20Information%20Fusion.pdf
- name: Code
  url: ''
---
