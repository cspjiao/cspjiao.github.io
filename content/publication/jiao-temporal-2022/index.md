---
title: Temporal Network Embedding for Link Prediction via VAE Joint Attention Mechanism
authors:
- Pengfei Jiao
- Xuan Guo
- Xin Jing
- Dongxiao He
- Huaming Wu
- Shirui Pan
- Maoguo Gong
- Wenjun Wang
date: '2022-12-01'
publishDate: '2024-03-12T04:12:18.374776Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Neural Networks and Learning Systems*'
doi: 10.1109/TNNLS.2021.3084957
abstract: 'Network representation learning or embedding aims to project the network
  into a low-dimensional space that can be devoted to different network tasks. Temporal
  networks are an important type of network whose topological structure changes over
  time. Compared with methods on static networks, temporal network embedding (TNE)
  methods are facing three challenges: 1) it cannot describe the temporal dependence
  across network snapshots; 2) the node embedding in the latent space fails to indicate
  changes in the network topology; and 3) it cannot avoid a lot of redundant computation
  via parameter inheritance on a series of snapshots. To overcome these problems,
  we propose a novel TNE method named temporal network embedding method based on the
  VAE framework (TVAE), which is based on a variational autoencoder (VAE) to capture
  the evolution of temporal networks for link prediction. It not only generates low-dimensional
  embedding vectors for nodes but also preserves the dynamic nonlinear features of
  temporal networks. Through the combination of a self-attention mechanism and recurrent
  neural networks, TVAE can update node representations and keep the temporal dependence
  of vectors over time. We utilize parameter inheritance to keep the new embedding
  close to the previous one, rather than explicitly using regularization, and thus,
  it is effective for large-scale networks. We evaluate our model and several baselines
  on synthetic data sets and real-world networks. The experimental results demonstrate
  that TVAE has superior performance and lower time cost compared with the baselines.'
tags:
- Link prediction
- Logic gates
- Matrix decomposition
- Network topology
- Predictive models
- self-attention mechanism
- Social networking (online)
- Task analysis
- temporal network embedding (TNE)
- Topology
- variational autoencoder (VAE)
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9449483
---
