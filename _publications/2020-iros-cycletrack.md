---
title: "Self-supervised Object Tracking with Cycle-consistent Siamese Networks"
collection: publications
category: conferences
permalink: /publication/2020-iros-cycletrack
excerpt: ''
date: 2020-09-01
venue: 'IROS'
authors: <b>Weihao Yuan</b>, Michael Yu Wang, Qifeng Chen
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2008.00637'
codeurl: 'https://github.com/weihaosky/CycleSiam'
citation: '<b>Weihao Yuan</b>, Michael Yu Wang, Qifeng Chen. “Self-supervised Object Tracking with Cycle-consistent Siamese Networks”, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, 2020.'
---
Self-supervised learning for visual object tracking possesses valuable advantages compared to supervised learning, such as the non-necessity of laborious human annotations and online training. In this work, we exploit an end-to-end Siamese network in a cycle-consistent self-supervised framework for object tracking. Self-supervision can be performed by taking advantage of the cycle consistency in the forward and backward tracking. To better leverage the end-to-end learning of deep networks, we propose to integrate a Siamese region proposal and mask regression network in our tracking framework so that a fast and more accurate tracker can be learned without the annotation of each frame. The experiments on the VOT dataset for visual object tracking and on the DAVIS dataset for video object segmentation propagation show that our method outperforms prior approaches on both tasks.