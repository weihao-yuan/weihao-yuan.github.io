---
title: "MulSMo: Multimodal Stylized Motion Generation by Bidirectional Control Flow"
collection: publications
category: preprint
permalink: /publication/others-2024-mulsmo
excerpt: '' 
date: 2024-12-01
venue: 'Arxiv'
authors: 'Zhe Li, Yisheng He, Lei Zhong, Weichao Shen, Qi Zuo, Lingteng Qiu, Zilong Dong, Laurence Tianruo Yang, <b>Weihao Yuan</b>†'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2401.14257'
# codeurl: ''
citation: 'Zhe Li, Yisheng He, Lei Zhong, Weichao Shen, Qi Zuo, Lingteng Qiu, Zilong Dong, Laurence Tianruo Yang, <b>Weihao Yuan</b>†. “MulSMo: Multimodal Stylized Motion Generation by Bidirectional Control Flow”.'
---
Generating motion sequences conforming to a target style while adhering to the given content prompts requires accommodating both the content and style. In existing methods, the information usually only flows from style to content, which may cause conflict between the style and content, harming the integration. Differently, in this work we build a bidirectional control flow between the style and the content, also adjusting the style towards the content, in which case the style-content collision is alleviated and the dynamics of the style is better preserved in the integration. Moreover, we extend the stylized motion generation from one modality, i.e. the style motion, to multiple modalities including texts and images through contrastive learning, leading to flexible style control on the motion generation. Extensive experiments demonstrate that our method significantly outperforms previous methods across different datasets, while also enabling multimodal signals control. The code of our method will be made publicly available.
