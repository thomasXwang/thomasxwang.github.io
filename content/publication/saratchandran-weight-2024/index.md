---
title: Weight Conditioning for Smooth Optimization of Neural Networks
authors:
- Hemanth Saratchandran
- Thomas X. Wang
- Simon Lucey
date: '2024-09-01'
publishDate: '2024-09-28T18:10:52.779487Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2409.03424
abstract: In this article, we introduce a novel normalization technique for neural
  network weight matrices, which we term weight conditioning. This approach aims to
  narrow the gap between the smallest and largest singular values of the weight matrices,
  resulting in better-conditioned matrices. The inspiration for this technique partially
  derives from numerical linear algebra, where well-conditioned matrices are known
  to facilitate stronger convergence results for iterative solvers. We provide a theoretical
  foundation demonstrating that our normalization technique smoothens the loss landscape,
  thereby enhancing convergence of stochastic gradient descent algorithms. Empirically,
  we validate our normalization across various neural network architectures, including
  Convolutional Neural Networks (CNNs), Vision Transformers (ViT), Neural Radiance
  Fields (NeRF), and 3D shape modeling. Our findings indicate that our normalization
  method is not only competitive but also outperforms existing weight normalization
  techniques from the literature.
links:
- name: URL
  url: http://arxiv.org/abs/2409.03424
---
