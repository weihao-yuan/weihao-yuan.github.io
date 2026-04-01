---
title: "DIM-SLAM: Dense RGB SLAM With Neural Implicit Maps"
collection: publications
category: conferences
permalink: /publication/2023-iclr-dimslam
excerpt: '' 
date: 2023-05-01
venue: 'ICLR'
authors: 'Heng Li, Xiaodong Gu, <b>Weihao Yuan</b>, Luwei Yang, Zilong Dong, Ping Tan'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2301.08930'
codeurl: 'http://poptree.github.io/DIM-SLAM/'
citation: 'Heng Li, Xiaodong Gu, <b>Weihao Yuan</b>, Luwei Yang, Zilong Dong, Ping Tan. “Dense RGB SLAM with Neural Implicit Maps“, International Conference on Learning Representations (ICLR). 2023.'
---
There is an emerging trend of using neural implicit functions for map representation in Simultaneous Localization and Mapping (SLAM). Some pioneer works have achieved encouraging results on RGB-D SLAM. In this paper, we present a dense RGB SLAM method with neural implicit map representation. To reach this challenging goal without depth input, we introduce a hierarchical feature volume to facilitate the implicit map decoder. This design effectively fuses shape cues across different scales to facilitate map reconstruction. Our method simultaneously solves the camera motion and the neural implicit map by matching the rendered and input video frames. To facilitate optimization, we further propose a photometric warping loss in the spirit of multi-view stereo to better constrain the camera pose and scene geometry. We evaluate our method on commonly used benchmarks and compare it with modern RGB and RGB-D SLAM systems. Our method achieves favorable results than previous methods and even surpasses some recent RGB-D SLAM methods.
