---
title: "OmniMotion: Multimodal Motion Generation with Continuous Masked Autoregression"
collection: publications
category: preprint
permalink: /publication/others-2025-omnimotion
excerpt: '' 
date: 2025-10-01
venue: 'Arxiv'
authors: 'Zhe Li, <b>Weihao Yuan</b>†, Weichao Shen, Siyu Zhu, Zilong Dong, Chang Xu†'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2510.14954'
# codeurl: ''
citation: 'Zhe Li, <b>Weihao Yuan</b>†, Weichao Shen, Siyu Zhu, Zilong Dong, Chang Xu†. “OmniMotion: Multimodal Motion Generation with Continuous Masked Autoregression”.'
---
Whole-body multi-modal human motion generation poses two primary challenges: creating an effective motion generation mechanism and integrating various modalities, such as text, speech, and music, into a cohesive framework. Unlike previous methods that usually employ discrete masked modeling or autoregressive modeling, we develop a continuous masked autoregressive motion transformer, where a causal attention is performed considering the sequential nature within the human motion. Within this transformer, we introduce a gated linear attention and an RMSNorm module, which drive the transformer to pay attention to the key actions and suppress the instability caused by either the abnormal movements or the heterogeneous distributions within multi-modalities. To further enhance both the motion generation and the multimodal generalization, we employ the DiT structure to diffuse the conditions from the transformer towards the targets. To fuse different modalities, AdaLN and cross-attention are leveraged to inject the text, speech, and music signals. Experimental results demonstrate that our framework outperforms previous methods across all modalities, including text-to-motion, speech-to-gesture, and music-to-dance.