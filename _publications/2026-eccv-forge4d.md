---
title: "Forge4D: Feed-Forward 4D Human Reconstruction and Interpolation from Uncalibrated Sparse-view Videos"
collection: publications
category: conferences
permalink: /publication/2026-eccv-forge4d
excerpt: '' 
date: 2026-06-01
venue: 'ECCV'
authors: 'Yingdong Hu, Yisheng He, Jinnan Chen, <b>Weihao Yuan</b>, Kejie Qiu, Zehong Lin, Siyu Zhu, Zilong Dong, Jun Zhang'
projecturl: 'https://zhenliuzju.github.io/huyingdong/Forge4D/'
paperurl: 'https://arxiv.org/abs/2509.24209'
codeurl: 'http://github.com/zhenliuZJU/Forge4D'
citation: 'Yingdong Hu, Yisheng He, Jinnan Chen, <b>Weihao Yuan</b>, Kejie Qiu, Zehong Lin, Siyu Zhu, Zilong Dong, Jun Zhang. “Forge4D: Feed-Forward 4D Human Reconstruction and Interpolation from Uncalibrated Sparse-view Videos”, European Conference on Computer Vision (ECCV). 2026.'
---
Instant reconstruction of dynamic 3D humans from uncalibrated sparse-view videos is critical for numerous downstream applications. Existing methods, however, are either limited by the slow reconstruction speeds or incapable of generating novel-time representations. To address these challenges, we propose Forge4D, a feed-forward 4D human reconstruction and interpolation model that efficiently reconstructs temporally aligned representations from uncalibrated sparse-view videos, enabling both novel view and novel time synthesis. Our model simplifies the 4D reconstruction and interpolation problem as a joint task of streaming 3D Gaussian reconstruction and dense motion prediction. For the task of streaming 3D Gaussian reconstruction, we first reconstruct static 3D Gaussians from uncalibrated sparse-view images and then introduce learnable state tokens to enforce temporal consistency in a memory-friendly manner by interactively updating shared information across different timestamps. For novel time synthesis, we design a novel motion prediction module to predict dense motions for each 3D Gaussian between two adjacent frames, coupled with an occlusion-aware Gaussian fusion process to interpolate 3D Gaussians at arbitrary timestamps. To overcome the lack of the ground truth for dense motion supervision, we formulate dense motion prediction as a dense point matching task and introduce a self-supervised retargeting loss to optimize this module. An additional occlusion-aware optical flow loss is introduced to ensure motion consistency with plausible human movement, providing stronger regularization. Extensive experiments demonstrate the effectiveness of our model on both in-domain and out-of-domain datasets.