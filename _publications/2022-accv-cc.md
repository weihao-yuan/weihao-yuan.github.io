---
title: "Cluster Contrast for Unsupervised Person Re-Identification"
collection: publications
category: conferences
permalink: /publication/2022-accv-cc
excerpt: '<span class="text-why-red">Citation: 400+</span>'
date: 2022-12-01
venue: 'ACCV'
authors: Zuozhuo Dai, Guangyuan Wang, <b>Weihao Yuan</b>, Siyu Zhu, Ping Tan
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2103.11568'
codeurl: 'https://github.com/alibaba/cluster-contrast'
citation: 'Zuozhuo Dai, Guangyuan Wang, <b>Weihao Yuan</b>, Siyu Zhu, Ping Tan. “Cluster Contrast for Unsupervised Person Re-Identification”, Asian Conference on Computer Vision (ACCV). IEEE, 2022.'
---
Estimating the accurate depth from a single image is challenging since it is inherently ambiguous and ill-posed. While recent works design increasingly complicated and powerful networks to directly regress the depth map, we take the path of CRFs optimization. Due to the expensive computation, CRFs are usually performed between neighborhoods rather than the whole graph. To leverage the potential of fully-connected CRFs, we split the input into windows and perform the FC-CRFs optimization within each window, which reduces the computation complexity and makes FC-CRFs feasible. To better capture the relationships between nodes in the graph, we exploit the multi-head attention mechanism to compute a multi-head potential function, which is fed to the networks to output an optimized depth map. Then we build a bottom-up-top-down structure, where this neural window FC-CRFs module serves as the decoder, and a vision transformer serves as the encoder. The experiments demonstrate that our method significantly improves the performance across all metrics on both the KITTI and NYUv2 datasets, compared to previous methods. Furthermore, the proposed method can be directly applied to panorama images and outperforms all previous panorama methods on the MatterPort3D dataset.
