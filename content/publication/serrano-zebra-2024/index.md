---
title: 'Zebra: In-Context and Generative Pretraining for Solving Parametric PDEs'
authors:
- Louis Serrano
- Armand Kassaï Koupaï
- Thomas X. Wang
- Pierre Erbacher
- Patrick Gallinari
date: '2024-10-01'
publishDate: '2024-10-08T14:54:30.620670Z'
publication_types:
- manuscript
publication: '*arXiv.org*'
abstract: Solving time-dependent parametric partial differential equations (PDEs)
  is challenging, as models must adapt to variations in parameters such as coefficients,
  forcing terms, and boundary conditions. Data-driven neural solvers either train
  on data sampled from the PDE parameters distribution in the hope that the model
  generalizes to new instances or rely on gradient-based adaptation and meta-learning
  to implicitly encode the dynamics from observations. This often comes with increased
  inference complexity. Inspired by the in-context learning capabilities of large
  language models (LLMs), we introduce Zebra, a novel generative auto-regressive transformer
  designed to solve parametric PDEs without requiring gradient adaptation at inference.
  By leveraging in-context information during both pre-training and inference, Zebra
  dynamically adapts to new tasks by conditioning on input sequences that incorporate
  context trajectories or preceding states. This approach enables Zebra to flexibly
  handle arbitrarily sized context inputs and supports uncertainty quantification
  through the sampling of multiple solution trajectories. We evaluate Zebra across
  a variety of challenging PDE scenarios, demonstrating its adaptability, robustness,
  and superior performance compared to existing approaches.
links:
- name: URL
  url: https://arxiv.org/abs/2410.03437v1
---
