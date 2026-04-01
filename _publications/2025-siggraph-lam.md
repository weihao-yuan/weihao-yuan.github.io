---
title: "LAM: Large Avatar Model for One-shot Animatable Gaussian Head"
collection: publications
category: conferences
permalink: /publication/2025-siggraph-lam
excerpt: '' 
date: 2025-08-01
venue: 'SIGGRAPH'
authors: 'Yisheng He, Xiaodong Gu, Xiaodan Ye, Chao Xu, Zhengyi Zhao, Yuan Dong, <b>Weihao Yuan</b>†, Zilong Dong, Liefeng Bo'
projecturl: 'https://aigc3d.github.io/projects/LAM/'
paperurl: 'https://arxiv.org/abs/2502.17796'
codeurl: 'https://github.com/aigc3d/LAM'
citation: 'Yisheng He, Xiaodong Gu, Xiaodan Ye, Chao Xu, Zhengyi Zhao, Yuan Dong, <b>Weihao Yuan</b>†, Zilong Dong, Liefeng Bo. “LAM: Large Avatar Model for One-shot Animatable Gaussian Head”, SIGGRAPH. 2025.'
---
We present LAM, an innovative Large Avatar Model for animatable Gaussian head reconstruction from a single image. Unlike previous methods that require extensive training on captured video sequences or rely on auxiliary neural networks for animation and rendering during inference, our approach generates Gaussian heads that are immediately animatable and renderable. Specifically, LAM creates an animatable Gaussian head in a single forward pass, enabling reenactment and rendering without additional networks or post-processing steps. This capability allows for seamless integration into existing rendering pipelines, ensuring real-time animation and rendering across a wide range of platforms, including mobile phones. The centerpiece of our framework is the canonical Gaussian attributes generator, which utilizes FLAME canonical points as queries. These points interact with multi-scale image features through a Transformer to accurately predict Gaussian attributes in the canonical space. The reconstructed canonical Gaussian avatar can then be animated utilizing standard linear blend skinning (LBS) with corrective blendshapes as the FLAME model did and rendered in real-time on various platforms. Our experimental results demonstrate that LAM outperforms state-of-the-art methods on existing benchmarks.