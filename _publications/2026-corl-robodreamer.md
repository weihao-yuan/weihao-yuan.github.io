---
title: "RoboDreamer: Anticipatory Humanoid Locomotion with Predictive State-Space Models"
collection: publications
category: conferences
permalink: /publication/2026-corl-robodreamer
excerpt: '' 
date: 2026-09-01
venue: 'CoRL'
authors: 'Zhe Li, Yangyang Wei, Xichen Yuan, Zhenzhe Zhang, <b>Weihao Yuan</b>, Shanghang Zhang, Jianfei Yang'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2606.11637'
# codeurl: ''
citation: 'Zhe Li, Yangyang Wei, Xichen Yuan, Zhenzhe Zhang, <b>Weihao Yuan</b>, Shanghang Zhang, Jianfei Yang. “RoboDreamer: Anticipatory Humanoid Locomotion with Predictive State-Space Models”, CoRL. 2026.'
---
Humanoid locomotion requires control policies that remain stable under imperfect sensing while exploiting temporal context for consistent motion. We present RoboDreamer, a two-stage teacher--student framework that combines next-observation consistency with randomized continuous temporal masking. A teacher is first trained on clean observations, and a student is then distilled under masked recent observations, encouraging the policy to infer missing current information from history. At inference, the same masking interface is reused for implicit closed-loop action refinement and optional multi-step action chunking. Mamba is used as the temporal backbone, while matched ablations show that masking/distillation provides a substantial part of the gain and Mamba contributes additional tracking improvements with real-time latency. Experiments in IsaacLab, MuJoCo, and on a Unitree G1 demonstrate robust motion tracking under observation masking and successful real-world deployment.