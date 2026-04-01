---
title: "An Optimization Framework to Enforce Multi-View Consistency for Texturing 3D Meshes Using Pre-Trained Text-2-Image Models"
collection: publications
category: conferences
permalink: /publication/2024-eccv-consistentex
excerpt: '' 
date: 2024-09-01
venue: 'ECCV'
authors: 'Zhengyi Zhao, Chen Song, Xiaodong Gu, Yuan Dong, Qi Zuo, <b>Weihao Yuan</b>, Liefeng Bo, Zilong Dong, Qixing Huang'
projecturl: 'https://aigc3d.github.io/ConsistenTex/'
paperurl: 'https://arxiv.org/abs/2403.15559'
# codeurl: ''
citation: 'Zhengyi Zhao, Chen Song, Xiaodong Gu, Yuan Dong, Qi Zuo, <b>Weihao Yuan</b>, Liefeng Bo, Zilong Dong, Qixing Huang. “Freditor: High-Fidelity and Transferable NeRF Editing by Frequency Decomposition”, European Conference on Computer Vision (ECCV). 2024.'
---
A fundamental problem in the texturing of 3D meshes using pre-trained text-to-image models is to ensure multi-view consistency. State-of-the-art approaches typically use diffusion models to aggregate multi-view inputs, where common issues are the blurriness caused by the averaging operation in the aggregation step or inconsistencies in local features. This paper introduces an optimization framework that proceeds in four stages to achieve multi-view consistency. Specifically, the first stage generates an over-complete set of 2D textures from a predefined set of viewpoints using an MV-consistent diffusion process. The second stage selects a subset of views that are mutually consistent while covering the underlying 3D model. We show how to achieve this goal by solving semi-definite programs. The third stage performs non-rigid alignment to align the selected views across overlapping regions. The fourth stage solves an MRF problem to associate each mesh face with a selected view. In particular, the third and fourth stages are iterated, with the cuts obtained in the fourth stage encouraging non-rigid alignment in the third stage to focus on regions close to the cuts. Experimental results show that our approach significantly outperforms baseline approaches both qualitatively and quantitatively.