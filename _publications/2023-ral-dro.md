---
title: "DRO: Deep Recurrent Optimizer for Video to Depth"
collection: publications
category: journals
permalink: /publication/2023-ral-dro
excerpt: '' 
date: 2023-03-01
venue: 'Robotics and Automation Letters (RA-L)'
authors: 'Xiaodong Gu*, <b>Weihao Yuan</b>*†, Zuozhuo Dai, Chengzhou Tang, Siyu Zhu, Ping Tan'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2103.13201'
codeurl: 'https://github.com/aliyun/dro-sfm'
citation: 'Xiaodong Gu*, <b>Weihao Yuan</b>*†, Zuozhuo Dai, Chengzhou Tang, Siyu Zhu, Ping Tan. “DRO: Deep Recurrent Optimizer for Video to Depth”, IEEE Robotics and Automation Letters (RAL). 2024.'
---
There are increasing interests of studying the video-to-depth (V2D) problem with machine learning techniques. While earlier methods directly learn a mapping from images to depth maps and camera poses, more recent works enforce multi-view geometry constraints through optimization embedded in the learning framework. This paper presents a novel optimization method based on recurrent neural networks to further exploit the potential of neural networks in V2D. Specifically, our neural optimizer alternately updates the depth and camera poses through iterations to minimize a feature-metric cost, and two gated recurrent units iteratively improve the results by tracing historical information. Extensive experimental results demonstrate that our method outperforms previous methods and is more efficient in computation and memory consumption than cost-volume-based methods. In particular, our self-supervised method outperforms previous supervised methods on the KITTI and ScanNet datasets.