---
title: "BARD: Bridging AutoRegressive and Diffusion Vision-Language Models Via Highly Efficient Progressive Block Merging and Stage-Wise Distillation"
collection: publications
category: conferences
permalink: /publication/2026-mm-bard
excerpt: '' 
date: 2026-07-01
venue: 'ACM MM'
authors: 'Baoyou Chen, Hanchen Xia, Peng Tu, Haojun Shi, Liwei Zhang, Yuxuan Yao, <b>Weihao Yuan</b>, Siyu Zhu'
projecturl: 'https://fudan-generative-vision.github.io/Bard-VL/'
paperurl: 'https://arxiv.org/abs/2604.16514'
codeurl: 'https://github.com/fudan-generative-vision/Bard-VL'
citation: 'Yingdong Hu, Yisheng He, Jinnan Chen, <b>Weihao Yuan</b>, Kejie Qiu, Zehong Lin, Siyu Zhu, Zilong Dong, Jun Zhang. “Forge4D: Feed-Forward 4D Human Reconstruction and Interpolation from Uncalibrated Sparse-view Videos”, ACM Multimedia (MM). 2026.'
---
Autoregressive vision-language models (VLMs) deliver strong multimodal capability, but their token-by-token decoding imposes a fundamental inference bottleneck. Diffusion VLMs offer a more parallel decoding paradigm, yet directly converting a pretrained autoregressive VLM into a large-block diffusion VLM (dVLM) often leads to substantial quality degradation. In this work, we present BARD, a simple and effective bridging framework that converts a pretrained autoregressive VLM into a same-architecture, decoding-efficient dVLM. Our approach combines progressive supervised block merging, which gradually enlarges the decoding block size, with stage-wise intra-dVLM distillation from a fixed small-block diffusion anchor to recover performance lost at larger blocks. We further incorporate a mixed noise scheduler to improve robustness and token revision during denoising, and memory-friendly training to enable efficient training on long multimodal sequences. A key empirical finding is that direct autoregressive-to-diffusion distillation is poorly aligned and can even hurt performance, whereas distillation within the diffusion regime is consistently effective. Experimental results show that, with ≤ 4.4M data, BARD-VL transfers strong multimodal capability from Qwen3-VL to a large-block dVLM. Remarkably, BARD-VL establishes a new SOTA among comparable-scale open dVLMs on our evaluation suite at both 4B and 8B scales. At the same time, BARD-VL achieves up to 3× decoding throughput speedup compared to the source model.