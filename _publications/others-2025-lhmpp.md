---
title: "LHM++: An Efficient Large Human Reconstruction Model for Pose-free Images to 3D"
collection: publications
category: preprint
permalink: /publication/others-2025-lhmpp
excerpt: '' 
date: 2025-06-01
venue: 'Arxiv'
authors: 'Lingteng Qiu, Peihao Li, Heyuan Li, Qi Zuo, Xiaodong Gu, Yuan Dong, <b>Weihao Yuan</b>, Rui Peng, Siyu Zhu, Xiaoguang Han, Guanying Chen, Zilong Dong'
projecturl: 'https://lingtengqiu.github.io/LHM++/'
paperurl: 'https://arxiv.org/abs/2506.13766'
codeurl: 'https://github.com/aigc3d/LHM-plusplus'
citation: 'Lingteng Qiu, Peihao Li, Heyuan Li, Qi Zuo, Xiaodong Gu, Yuan Dong, <b>Weihao Yuan</b>, Rui Peng, Siyu Zhu, Xiaoguang Han, Guanying Chen, Zilong Dong. “LHM++: An Efficient Large Human Reconstruction Model for Pose-free Images to 3D”.'
---
Reconstructing animatable 3D humans from casually captured images of articulated subjects without camera or pose information is highly practical but remains challenging due to view misalignment, occlusions, and the absence of structural priors. In this work, we present LHM++, an efficient large-scale human reconstruction model that generates high-quality, animatable 3D avatars within seconds from one or multiple pose-free images. At its core is an Encoder-Decoder Point-Image Transformer architecture that progressively encodes and decodes 3D geometric point features to improve efficiency, while fusing hierarchical 3D point features with image features through multimodal attention. The fused features are decoded into 3D Gaussian splats to recover detailed geometry and appearance. To further enhance visual fidelity, we introduce a lightweight 3D-aware neural animation renderer that refines the rendering quality of reconstructed avatars in real time. Extensive experiments show that our method produces high-fidelity, animatable 3D humans without requiring camera or pose annotations.