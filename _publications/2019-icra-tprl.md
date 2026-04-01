---
title: "Reinforcement Learning in Topology-based Representation for Human Body Movement with Whole Arm Manipulation"
collection: publications
category: conferences
permalink: /publication/2019-icra-tprl
excerpt: ''
date: 2019-05-01
venue: 'ICRA'
authors: <b>Weihao Yuan</b>, Kaiyu Hang, Haoran Song, Danica Kragic, Michael Yu Wang, Johannes A. Stork
# projecturl: ''
paperurl: 'https://arxiv.org/abs/1809.04322'
# codeurl: ''
citation: '<b>Weihao Yuan</b>, Kaiyu Hang, Haoran Song, Danica Kragic, Michael Yu Wang, Johannes A. Stork. “Reinforcement Learning in Topology-based Representation for Human Body Movement with Whole Arm Manipulation”, IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2019.'
---
Moving a human body or a large and bulky object can require the strength of whole arm manipulation (WAM). This type of manipulation places the load on the robot's arms and relies on global properties of the interaction to succeed---rather than local contacts such as grasping or non-prehensile pushing. In this paper, we learn to generate motions that enable WAM for holding and transporting of humans in certain rescue or patient care scenarios. We model the task as a reinforcement learning problem in order to provide a behavior that can directly respond to external perturbation and human motion. For this, we represent global properties of the robot-human interaction with topology-based coordinates that are computed from arm and torso positions. These coordinates also allow transferring the learned policy to other body shapes and sizes. For training and evaluation, we simulate a dynamic sea rescue scenario and show in quantitative experiments that the policy can solve unseen scenarios with differently-shaped humans, floating humans, or with perception noise. Our qualitative experiments show the subsequent transporting after holding is achieved and we demonstrate that the policy can be directly transferred to a real world setting.