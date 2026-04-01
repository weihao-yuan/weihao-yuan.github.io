---
title: "End-to-End Nonprehensile Rearrangement with Deep Reinforcement Learning and Simulation-to-Reality Transfer"
collection: publications
category: journals
permalink: /publication/2019-ras-nrrlt
excerpt: ''
date: 2019-10-01
venue: 'Robotics and Autonomous Systems (RAS)'
authors: <b>Weihao Yuan</b>, Kaiyu Hang, Danica Kragic, Michael Yu Wang, Johannes A. Stork
# projecturl: ''
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0921889018304913'
# codeurl: ''
citation: '<b>Weihao Yuan</b>, Kaiyu Hang, Danica Kragic, Michael Yu Wang, Johannes A. Stork. “End-to-End Nonprehensile Rearrangement with Deep Reinforcement Learning and Simulation-to-Reality Transfer”, Robotics and Autonomous Systems (RAS). 2019.'
---
Nonprehensile rearrangement is the problem of controlling a robot to interact with objects through pushing actions in order to reconfigure the objects into a predefined goal pose. In this work, we rearrange one object at a time in an environment with obstacles using an end-to-end policy that maps raw pixels as visual input to control actions without any form of engineered feature extraction. To reduce the amount of training data that needs to be collected using a real robot, we propose a simulation-to-reality transfer approach. In the first step, we model the nonprehensile rearrangement task in simulation and use deep reinforcement learning to learn a suitable rearrangement policy, which requires in the order of hundreds of thousands of example actions for training. Thereafter, we collect a small dataset of only 70 episodes of real-world actions as supervised examples for adapting the learned rearrangement policy to real-world input data. In this process, we make use of newly proposed strategies for improving the reinforcement learning process, such as heuristic exploration and the curation of a balanced set of experiences. We evaluate our method in both simulation and real setting using a Baxter robot to show that the proposed approach can effectively improve the training process in simulation, as well as efficiently adapt the learned policy to the real world application, even when the camera pose is different from simulation. Additionally, we show that the learned system not only can provide adaptive behavior to handle unforeseen events during executions, such as distraction objects, sudden changes in positions of the objects, and obstacles, but also can deal with obstacle shapes that were not present in the training process.