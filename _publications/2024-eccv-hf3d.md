---
title: "High-Fidelity 3D Textured Shapes Generation by Sparse Encoding and Adversarial Decoding"
collection: publications
category: conferences
permalink: /publication/2024-eccv-hf3d
excerpt: '' 
date: 2024-09-01
venue: 'ECCV'
authors: 'Qi Zuo, Xiaodong Gu, Yuan Dong, Zhengyi Zhao, <b>Weihao Yuan</b>, Lingteng Qiu, Liefeng Bo, Zilong Dong'
# projecturl: ''
paperurl: 'https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01495.pdf'
# codeurl: ''
citation: 'Qi Zuo, Xiaodong Gu, Yuan Dong, Zhengyi Zhao, <b>Weihao Yuan</b>, Lingteng Qiu, Liefeng Bo, Zilong Dong. “High-Fidelity 3D Textured Shapes Generation by Sparse Encoding and Adversarial Decoding”, European Conference on Computer Vision (ECCV). 2024.'
---
3D vision is inherently characterized by sparse spatial structures, which propels the necessity for an efficient paradigm tailored to 3D generation. Another discrepancy is the amount of training data, which undeniably affects generalization if we only use limited 3D data. To solve these, we design a 3D generation framework that maintains most of the building blocks of StableDiffusion with minimal adaptations for textured shape generation. We design a Sparse Encoding Module for details preservation and an Adversarial Decoding Module for better shape recovery. Moreover, we clean up data and build a benchmark on the biggest 3D dataset (Objaverse). We drop the concept of ‘specific class’ and treat the 3D Textured Shapes Generation as an open-vocabulary problem. We first validate our network design on ShapeNetV2 with 55K samples on single-class unconditional generation and multi-class conditional generation tasks. Then we report metrics on processed G-Objaverse with 200K samples on the image conditional generation task. Extensive experiments demonstrate our proposal outperforms SOTA methods and takes a further step towards open-vocabulary 3D generation