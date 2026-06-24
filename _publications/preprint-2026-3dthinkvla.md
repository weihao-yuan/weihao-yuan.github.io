---
title: "3DThinkVLA: Endowing Vision-Language-Action Models with Latent 3D Priors via 3D-Thinking-Guided Co-training"
collection: publications
category: preprint
permalink: /publication/preprint-2026-3dthinkvla
excerpt: '' 
date: 2026-12-01
venue: 'Arxiv'
authors: 'Jiaxin Shi, Xidong Zhang, Fucai Zhu, Zhe Li, Siyu Zhu, <b>Weihao Yuan</b>†'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2605.27154'
# codeurl: ''

citation: 'Jiaxin Shi, Xidong Zhang, Fucai Zhu, Zhe Li, Siyu Zhu, <b>Weihao Yuan</b>†. “3DThinkVLA: Endowing Vision-Language-Action Models with Latent 3D Priors via 3D-Thinking-Guided Co-training”.'
---
We propose a 3D-thinking-guided co-training framework that enables vision-language-action (VLA) models to perform 3D spatial reasoning implicitly during action prediction. Our core insight is that 3D geometry perception and 3D spatial reasoning are distinct capabilities that can be disentangled and injected at different feature hierarchies. During training, three tightly coupled components work in concert primarily within the latent space: (1) To gain geometric priors, a latent 3D geometry perception module aligns intermediate visual features with a 3D foundation model, acquiring low-level geometric cues without architectural modifications to the VLM backbone. (2) Complementing this, an online 3D reasoning distillation module mitigates the prompt-induced reasoning gap via a shared reasoning anchor token. During 3D VLM co-training, this anchor is emitted as the first output token to robustly encode spatial priors. During VLA training, it serves as an input token inserted between the task and action instructions, transferring high-level spatial thinking from explicit teacher reasoning prompts to student action prompts without chain-of-thought text generation. (3) These disentangled geometric and reasoning features are then united by a spatially augmented action integration, which jointly injects them into the action-query tokens as hierarchical spatial conditions to prevent action shortcuts. At deployment, our method retains only its lightweight adapters to perform implicit 3D reasoning, discarding the 3D foundation model and the teacher branch used for supervision. Consequently, it operates purely on 2D images without 3D sensors, external models, or explicit text generation while preventing catastrophic forgetting of the pretrained VLM, achieving state-of-the-art performance on LIBERO, LIBERO-PLUS, SimplerEnv, and real-world manipulation tasks.