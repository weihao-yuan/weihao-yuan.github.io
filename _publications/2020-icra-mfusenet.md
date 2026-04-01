---
title: "MFuseNet: Robust Depth Estimation with Learned Multiscopic Fusion"
collection: publications
category: conferences
permalink: /publication/2020-icra-mfusenet
excerpt: ''
date: 2020-05-01
venue: 'ICRA'
authors: <b>Weihao Yuan</b>, Rui Fan, Michael Yu Wang, Qifeng Chen
projecturl: 'https://sites.google.com/view/multiscopic'
paperurl: 'https://ieeexplore.ieee.org/document/9000612'
codeurl: 'https://github.com/weihaosky/MFuseNet'
citation: '<b>Weihao Yuan</b>, Rui Fan, Michael Yu Wang, Qifeng Chen. “MFuseNet: Robust Depth Estimation with Learned Multiscopic Fusion”, IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2020.'
---
We design a multiscopic vision system that utilizes a low-cost monocular RGB camera to acquire accurate depth estimation. Unlike multi-view stereo with images captured at unconstrained camera poses, the proposed system controls the motion of a camera to capture a sequence of images in horizontally or vertically aligned positions with the same parallax. In this system, we propose a new heuristic method and a robust learning-based method to fuse multiple cost volumes between the reference image and its surrounding images. To obtain training data, we build a synthetic dataset with multiscopic images. The experiments on the real-world Middlebury dataset and real robot demonstration show that our multiscopic vision system outperforms traditional two-frame stereo matching methods in depth estimation.