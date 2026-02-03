---
title: "DREWM: A Decision-Refined World Model for End-to-End Autonomous Driving"
collection: publications
category: manuscripts
permalink: /publication/2025-11-17-paper-title-drewm
excerpt: 'End-to-End Autonomous Driving, Decision-Making, World Model.'
date: 2025-11-17
venue: 'IEEE Transactions on Vehicular Technology'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11250785'
citation: 'J. Du, Y. Liang, J. Geng, Y. Huang and H. Chen, "DREWM: A Decision-Refined World Model for End-to-End Autonomous Driving," in IEEE Transactions on Vehicular Technology. '
---
End-to-end autonomous driving systems have garnered attention for their potential to optimize and represent the entire driving task in an integrated manner. However, current end-to-end approaches tend to prioritize optimizations and hidden states, often overlooking the decision-making framework, which poses ongoing challenges in safety and comfort. This study introduces DREWM, A Decision-Refined End-to-End World Model, which leverages the world model alongside a sample-evaluation decision-making framework to improve decision-making efficiency, safety, and comfort. By incorporating a trajectory sampling and optimization strategy within a world model, we establish a hybrid decision framework that enables robust vehicle control and optimized route planning in complex driving conditions. Specifically, this work first applies a generative perception network to extract both two-dimensional and three-dimensional perception features from monocular camera inputs, followed by distribution-fitting sampling to obtain environmental dynamic information. Then the Self-Transformer architecture enhances the model's capability to represent implicit features of environmental dynamic information. In the decoding phase, safety and comfort metrics guide the selection and adjustment of pre-generated trajectories, leading to control outputs. Experimental results show that the proposed method achieves higher levels of safety and driving comfort across diverse scenarios compared to approaches solely based on deep learning. Testing in CARLA environments indicates that DREWM outperforms baseline models and other state-of-the-art methods in Driving Score, offering a promising solution for real-world applications of end-to-end autonomous driving systems.
