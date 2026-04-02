---
title: "PanoLAM: Large Avatar Model for Gaussian Full-Head Synthesis from One-shot Unposed Image"
collection: publications
category: preprint
permalink: /publication/others-2025-panolam
excerpt: '' 
date: 2025-09-01
venue: 'Arxiv'
authors: 'Peng Li, Yisheng He, Yingdong Hu, Yuan Dong, <b>Weihao Yuan</b>, Yuan Liu, Siyu Zhu, Gang Cheng, Zilong Dong, Yike Guo'
projecturl: 'https://panolam.github.io/'
paperurl: 'https://arxiv.org/abs/2509.24209'
# codeurl: ''
citation: 'Peng Li, Yisheng He, Yingdong Hu, Yuan Dong, <b>Weihao Yuan</b>, Yuan Liu, Siyu Zhu, Gang Cheng, Zilong Dong, Yike Guo. “PanoLAM: Large Avatar Model for Gaussian Full-Head Synthesis from One-shot Unposed Image”.'
---
We present a feed-forward framework for Gaussian full-head synthesis from a single unposed image. Unlike previous work that relies on time-consuming GAN inversion and test-time optimization, our framework can reconstruct the Gaussian full-head model given a single unposed image in a single forward pass. This enables fast reconstruction and rendering during inference. To mitigate the lack of large-scale 3D head assets, we propose a large-scale synthetic dataset from trained 3D GANs and train our framework using only synthetic data. For efficient high-fidelity generation, we introduce a coarse-to-fine Gaussian head generation pipeline, where sparse points from the FLAME model interact with the image features by transformer blocks for feature extraction and coarse shape reconstruction, which are then densified for high-fidelity reconstruction. To fully leverage the prior knowledge residing in pretrained 3D GANs for effective reconstruction, we propose a dual-branch framework that effectively aggregates the structured spherical triplane feature and unstructured point-based features for more effective Gaussian head reconstruction. Experimental results show the effectiveness of our framework towards existing work.