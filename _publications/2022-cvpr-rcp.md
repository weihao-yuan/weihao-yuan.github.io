---
title: "RCP: Recurrent Closest Point for Scene Flow Estimation on 3D Point Clouds"
collection: publications
category: conferences
permalink: /publication/2022-cvpr-rcp
excerpt: '<span class="text-why-red">Oral Presentation</span>'
date: 2022-06-01
venue: 'CVPR'
authors: 'Xiaodong Gu, Chengzhou Tang, <b>Weihao Yuan</b>, Zuozhuo Dai, Siyu Zhu, Ping Tan'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2205.11028'
codeurl: 'https://github.com/AlibabaResearch/rcp'
citation: 'Xiaodong Gu, Chengzhou Tang, <b>Weihao Yuan</b>, Zuozhuo Dai, Siyu Zhu, Ping Tan. “RCP: Recurrent Closest Point for Scene Flow Estimation on 3D Point Clouds”, IEEE Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2022. <b>Oral Presentation</b>'
---

3D motion estimation including scene flow and point cloud registration has drawn increasing interest. Inspired by 2D flow estimation, recent methods employ deep neural networks to construct the cost volume for estimating accurate 3D flow. However, these methods are limited by the fact that it is difficult to define a search window on point clouds because of the irregular data structure. In this paper, we avoid this irregularity by a simple yet effective method. We decompose the problem into two interlaced stages, where the 3D flows are optimized point-wisely at the first stage and then globally regularized in a recurrent network at the second stage. Therefore, the recurrent network only receives the regular point-wise information as the input. In the experiments, we evaluate the proposed method on both the 3D scene flow estimation and the point cloud registration task. For 3D scene flow estimation, we make comparisons on the widely used FlyingThings3D and KITTIdatasets. For point cloud registration, we follow previous works and evaluate the data pairs with large pose and partially overlapping from ModelNet40. The results show that our method outperforms the previous method and achieves a new state-of-the-art performance on both 3D scene flow estimation and point cloud registration, which demonstrates the superiority of the proposed zero-order method on irregular point cloud data.
