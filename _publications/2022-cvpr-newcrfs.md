---
title: "NeWCRFs: Neural Window Fully-connected CRFs for Monocular Depth Estimation"
collection: publications
category: conferences
permalink: /publication/2022-cvpr-newcrfs
excerpt: '<span class="text-why-red">Rank 1st on the KITTI depth online benchmark from 14-10-2021 to 13-03-2022<br>Citation: 600+</span>' 
date: 2022-06-01
venue: 'CVPR'
authors: '<b>Weihao Yuan</b>, Xiaodong Gu, Zuozhuo Dai, Siyu Zhu, Ping Tan'
projecturl: 'https://weihaosky.github.io/former3d/'
paperurl: 'https://arxiv.org/abs/2301.13510'
codeurl: 'https://github.com/aliyun/NeWCRFs'
citation: '<b>Weihao Yuan</b>, Xiaodong Gu, Zuozhuo Dai, Siyu Zhu, Ping Tan. “NeW CRFs: Neural Window Fully-connected CRFs for Monocular Depth Estimation”, IEEE Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2022.'
---
Estimating the accurate depth from a single image is challenging since it is inherently ambiguous and ill-posed. While recent works design increasingly complicated and powerful networks to directly regress the depth map, we take the path of CRFs optimization. Due to the expensive computation, CRFs are usually performed between neighborhoods rather than the whole graph. To leverage the potential of fully-connected CRFs, we split the input into windows and perform the FC-CRFs optimization within each window, which reduces the computation complexity and makes FC-CRFs feasible. To better capture the relationships between nodes in the graph, we exploit the multi-head attention mechanism to compute a multi-head potential function, which is fed to the networks to output an optimized depth map. Then we build a bottom-up-top-down structure, where this neural window FC-CRFs module serves as the decoder, and a vision transformer serves as the encoder. The experiments demonstrate that our method significantly improves the performance across all metrics on both the KITTI and NYUv2 datasets, compared to previous methods. Furthermore, the proposed method can be directly applied to panorama images and outperforms all previous panorama methods on the MatterPort3D dataset.
