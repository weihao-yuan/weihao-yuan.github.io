---
title: "TacMind: Benchmarking and Modeling Tactile Interaction States for Robotic Manipulation"
collection: publications
category: preprint
permalink: /publication/preprint-2026-tacmind
excerpt: '' 
date: 2026-12-01
venue: 'Arxiv'
authors: 'Jiaxin Shi, Zibin Wu, Yichi Zhang, Jianghua Duan, Siyu Zhu, <b>Weihao Yuan</b>†'
projecturl: 'https://tacmind-bench.github.io/'
paperurl: 'https://arxiv.org/abs/2611.00455'
codeurl: 'https://github.com/Tacmind-Bench/TacMind'

citation: 'Jiaxin Shi, Zibin Wu, Yichi Zhang, Jianghua Duan, Siyu Zhu, <b>Weihao Yuan</b>†. “TacMind: Benchmarking and Modeling Tactile Interaction States for Robotic Manipulatio”.'
---
Tactile sensing provides robots with direct observations of contact physics, local geometry, and interaction dynamics, making it a vital source of feedback for contact-rich manipulation. However, existing tactile manipulation studies are often developed and evaluated within specific task settings, making it difficult to systematically compare how tactile information contributes under different interaction conditions. In this work, we develop a benchmark in simulation comprising 128 tasks organized around three complementary evaluation regimes: Precise, Recognition, and Dynamic. The benchmark further includes controlled static and dynamic task variants and 12 perturbation settings for evaluating robustness under changes in visual and physical conditions. These settings motivate studying tactile information as a temporally evolving interaction representation rather than only as an instantaneous observation. We therefore propose an action-conditioned latent predictive world model that integrates tactile history and learns a tactile state through prediction of future tactile latents. Building on this representation, we design a model that conditions action generation on the learned tactile state and uses predicted future tactile information to refine candidate actions through predictive tactile reflection. Experiments on the proposed benchmark show consistent gains from incorporating tactile information across the evaluated regimes.