---
title: "LaMP: Language-Motion Pretraining for Motion Generation, Retrieval, and Captioning"
collection: publications
category: conferences
permalink: /publication/2025-iclr-lamp
excerpt: '' 
date: 2025-05-01
venue: 'ICLR'
authors: 'Zhe Li*, <b>Weihao Yuan</b>*, Yisheng He, Lingteng Qiu, Shenhao Zhu, Xiaodong Gu, Weichao Shen, Yuan Dong, Zilong Dong, Laurence T. Yang'
projecturl: 'https://aigc3d.github.io/LaMP/'
paperurl: 'https://arxiv.org/abs/2410.07093'
codeurl: 'https://github.com/gentlefress/LaMP'
citation: 'Zhe Li*, <b>Weihao Yuan</b>*, Yisheng He, Lingteng Qiu, Shenhao Zhu, Xiaodong Gu, Weichao Shen, Yuan Dong, Zilong Dong, Laurence T. Yang. “LaMP: Language-Motion Pretraining for Motion Generation, Retrieval, and Captioning”, International Conference on Learning Representations (ICLR). 2025.'
---
Language plays a vital role in the realm of human motion. Existing methods have largely depended on CLIP text embeddings for motion generation, yet they fall short in effectively aligning language and motion due to CLIP's pretraining on static image-text pairs. This work introduces LaMP, a novel Language-Motion Pretraining model, which transitions from a language-vision to a more suitable language-motion latent space. It addresses key limitations by generating motion-informative text embeddings, significantly enhancing the relevance and semantics of generated motion sequences. With LaMP, we advance three key tasks: text-to-motion generation, motion-text retrieval, and motion captioning through aligned language-motion representation learning. For generation, we utilize LaMP to provide the text condition instead of CLIP, and an autoregressive masked prediction is designed to achieve mask modeling without rank collapse in transformers. For retrieval, motion features from LaMP's motion transformer interact with query tokens to retrieve text features from the text transformer, and vice versa. For captioning, we finetune a large language model with the language-informative motion features to develop a strong motion captioning model. In addition, we introduce the LaMP-BertScore metric to assess the alignment of generated motions with textual descriptions. Extensive experimental results on multiple datasets demonstrate substantial improvements over previous methods across all three tasks.