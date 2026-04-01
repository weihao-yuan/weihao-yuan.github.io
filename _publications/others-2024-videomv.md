---
title: "VideoMV: Consistent Multi-View Generation Based on Large Video Generative Model"
collection: publications
category: others
permalink: /publication/others-2024-videomv
excerpt: '' 
date: 2024-03-01
venue: 'Arxiv'
authors: 'Qi Zuo, Xiaodong Gu, Lingteng Qiu, Yuan Dong, Zhengyi Zhao, <b>Weihao Yuan</b>, Rui Peng, Siyu Zhu, Zilong Dong, Liefeng Bo, Qixing Huang'
projecturl: 'http://aigc3d.github.io/VideoMV'
paperurl: 'https://arxiv.org/abs/2403.12010'
codeurl: 'https://github.com/alibaba/VideoMV'
citation: 'Qi Zuo, Xiaodong Gu, Lingteng Qiu, Yuan Dong, Zhengyi Zhao, <b>Weihao Yuan</b>, Rui Peng, Siyu Zhu, Zilong Dong, Liefeng Bo, Qixing Huang. “VideoMV: Consistent Multi-View Generation Based on Large Video Generative Model”.'
---
Generating multi-view images based on text or single-image prompts is a critical capability for the creation of 3D content. Two fundamental questions on this topic are what data we use for training and how to ensure multi-view consistency. This paper introduces a novel framework that makes fundamental contributions to both questions. Unlike leveraging images from 2D diffusion models for training, we propose a dense consistent multi-view generation model that is fine-tuned from off-the-shelf video generative models. Images from video generative models are more suitable for multi-view generation because the underlying network architecture that generates them employs a temporal module to enforce frame consistency. Moreover, the video data sets used to train these models are abundant and diverse, leading to a reduced train-finetuning domain gap. To enhance multi-view consistency, we introduce a 3D-Aware Denoising Sampling, which first employs a feed-forward reconstruction module to get an explicit global 3D model, and then adopts a sampling strategy that effectively involves images rendered from the global 3D model into the denoising sampling loop to improve the multi-view consistency of the final images. As a by-product, this module also provides a fast way to create 3D assets represented by 3D Gaussians within a few seconds. Our approach can generate 24 dense views and converges much faster in training than state-of-the-art approaches (4 GPU hours versus many thousand GPU hours) with comparable visual quality and consistency. By further fine-tuning, our approach outperforms existing state-of-the-art methods in both quantitative metrics and visual effects.