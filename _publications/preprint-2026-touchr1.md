---
title: "Touch-R1: Reinforcing Touch Reasoning in MLLMs"
collection: publications
category: preprint
permalink: /publication/preprint-2026-touchr1
excerpt: '' 
date: 2026-05-01
venue: 'Arxiv'
authors: 'Yingxin Lai, Yafei Zhou, Fucai Zhu, Siyu Zhu, <b>Weihao Yuan</b>†'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2605.27154'
# codeurl: ''

citation: 'Yingxin Lai, Yafei Zhou, Fucai Zhu, Siyu Zhu, <b>Weihao Yuan</b>†. “Touch-R1: Reinforcing Touch Reasoning in MLLMs”.'
---
While rule-based reinforcement learning has recently catalyzed explicit reasoning in multimodal models, tactile reasoning remains largely underexplored. Existing tactile-language models primarily rely on supervised or contrastive objectives, which limits their capacity to ground predictions in physical evidence or rectify misleading visual priors. Tactile reasoning introduces two modality-specific challenges: the ordinal nature of physical attributes (e.g., hardness, roughness) and the cross-sensor distribution shifts inherent in optical tactile hardware. In this work, we introduce TouchReason-1M, a large-scale multimodal dataset comprising over 1M synchronized tactile pairs across four distinct sensors, and TouchReason-Bench, a rigorous framework for evaluating tactile perception and visual-tactile conflict resolution. Building upon these, we propose Touch-R1, a tactile reasoning MLLM based on Qwen2.5-VL-7B. Touch-R1 is trained via a tactile-grounded GRPO objective that combines ordinal-aware accuracy, cross-sensor physical consistency, structured-format control, and an input-side tactile grounding objective. Specifically, the tactile-use reward assigns credit only when authentic tactile inputs yield superior correctness relative to counterfactual controls where the tactile stream is removed, shuffled, or noise-masked. On TouchReason-Bench, Touch-R1-7B outperforms Octopi-13B by 18.4% and GPT-4o by 24.7% on average. Its structured reasoning traces reveal emergent behaviors of probing, comparison, and revision, demonstrating that R1-style reasoning can be effectively grounded in physical contact.