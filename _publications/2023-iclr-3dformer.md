---
title: "3D-Former: Monocular Scene Reconstruction with SDF 3D Transformers"
collection: publications
category: conferences
permalink: /publication/2023-iclr-3dformer
excerpt: '' 
date: 2023-05-01
venue: 'ICLR'
authors: '<b>Weihao Yuan</b>, Xiaodong Gu, Heng Li, Zilong Dong, Siyu Zhu'
projecturl: 'https://weihaosky.github.io/sdfformer/'
paperurl: 'https://arxiv.org/abs/2301.13510'
codeurl: 'https://github.com/alibaba-damo-academy/former3d'
citation: '<b>Weihao Yuan</b>, Xiaodong Gu, Heng Li, Zilong Dong, Siyu Zhu. “3D Former: Monocular Scene Reconstruction with 3D SDF Transformers“, International Conference on Learning Representations (ICLR). 2023.'
---
Monocular scene reconstruction from posed images is challenging due to the complexity of a large environment. Recent volumetric methods learn to directly predict the TSDF volume and have demonstrated promising results in this task. However, most methods focus on how to extract and fuse the 2D features to a 3D feature volume, but none of them improve the way how the 3D volume is aggregated. In this work, we propose an SDF transformer network, which replaces the role of 3D CNN for better 3D feature aggregation. To reduce the explosive computation complexity of the 3D multi-head attention, we propose a sparse window attention module, where the attention is only calculated between the non-empty voxels within a local window. Then a top-down-bottom-up 3D attention network is built for 3D feature aggregation, where a dilate-attention structure is proposed to prevent geometry degeneration, and two global modules are employed to equip with global receptive fields. The experiments on multiple datasets show that this 3D transformer network generates a more accurate and complete reconstruction, which outperforms previous methods by a large margin. Remarkably, the mesh accuracy is improved by 41.8%, and the mesh completeness is improved by 25.3% on the ScanNet dataset.
