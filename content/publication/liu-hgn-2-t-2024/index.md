---
title: 'HGN2T: A Simple but Plug-and-Play Framework Extending HGNNs on Heterogeneous
  Temporal Graphs'
authors:
- Huan Liu
- Pengfei Jiao
- Xuan Guo
- Huaming Wu
- Mengzhou Gao
- Jilin Zhang
date: '2024-02-01'
publishDate: '2024-03-12T01:17:25.014265Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Big Data*'
doi: 10.1109/TBDATA.2024.3366085
abstract: Heterogeneous graphs (HGs) with multiple entity and relation types are common
  in real-world networks. Heterogeneous graph neural networks (HGNNs) have shown promise
  for learning HG representations. However, most HGNNs are designed for static HGs
  and are not compatible with heterogeneous temporal graphs (HTGs). A few existing
  works have focused on HTG representation learning but they care more about how to
  capture the dynamic evolutions and less about their compatibility with those well-designed
  static HGNNs. They also handle graph structure and temporal dependency learning
  separately, ignoring that HTG evolutions are influenced by both nodes and relationships.
  To address this, we propose HGN2T, a simple and general framework that makes static
  HGNNs compatible with HTGs. HGN2T is plug-and-play, enabling static HGNNs to leverage
  their graph structure learning strengths. To capture the relationship-influenced
  evolutions, we design a special mechanism coupling both the HGNN and sequential
  model. Finally, through joint optimization by both detection and prediction tasks,
  the learned representations can fully capture temporal dependencies from historical
  information. We conduct several empirical evaluation tasks, and the results show
  our HGN2T can adapt static HGNNs to HTGs and overperform existing methods for HTGs.
links:
- name: URL
  url: https://www.computer.org/csdl/journal/bd/5555/01/10436338/1UwUQmzlWq4
---
