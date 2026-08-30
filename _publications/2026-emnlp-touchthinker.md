---
title: "TouchThinker: Scaling Tactile Commonsense Reasoning to the Open World with Large-scale Data and Action-aware Representation"
collection: publications
category: conferences
permalink: /publication/2026-emnlp-touchthinker
excerpt: '' 
date: 2026-08-01
venue: 'EMNLP'
authors: 'Kailin Lyu, Di Wu, Pengwei Zhang, Yuhang Zheng, Yingxin Lai, Long Xiao, Kangyi Wu, Pengna Li, Chen Gao, Lianyu Hu, Xiaobin Hu, Jie Hao, Ce Hao, <b>Weihao Yuan</b>, Shuicheng Yan'
projecturl: 'https://github.com/lvkailin0118/TouchThinker'
paperurl: 'https://arxiv.org/abs/2606.11637'
codeurl: 'https://github.com/lvkailin0118/TouchThinker'
citation: 'Kailin Lyu, Di Wu, Pengwei Zhang, Yuhang Zheng, Yingxin Lai, Long Xiao, Kangyi Wu, Pengna Li, Chen Gao, Lianyu Hu, Xiaobin Hu, Jie Hao, Ce Hao, <b>Weihao Yuan</b>, Shuicheng Yan. “TouchThinker: Scaling Tactile Commonsense Reasoning to the Open World with Large-scale Data and Action-aware Representation”, EMNLP. 2026.'
---
Touch is a key modality for embodied agents to understand the physical world. Although recent work has incorporated tactile signals into language systems for tactile commonsense reasoning, scaling such systems to realistic open-world settings remains challenging due to two key bottlenecks: (1) current tactile reasoning datasets remain limited in format and scale, providing insufficient supervision for reasoning from tactile observations to physical commonsense and hindering the learning of transferable tactile commonsense; (2) tactile signals are inherently redundant and action-specific, yet existing methods often overlook these properties, resulting in inefficient representations with limited semantic expressiveness. To address these limitations, we propose TouchThinker, a tactile-language framework that scales tactile commonsense reasoning to the open world from both data and representation perspectives. First, we construct TouchThinker-1M, a million-scale, multi-source tactile reasoning dataset covering 415 objects, 8 scenarios, and 7 sensor types, providing a solid data foundation for open-world generalization. We further introduce TouchThinker-Bench, an open-world benchmark with more realistic and diverse tasks. Then, we propose action-aware modeling mechanism to improve tactile representation efficiency and enable efficient reasoning. Experimental results demonstrate that TouchThinker achieves competitive performance against state-of-the-art models across multiple datasets.