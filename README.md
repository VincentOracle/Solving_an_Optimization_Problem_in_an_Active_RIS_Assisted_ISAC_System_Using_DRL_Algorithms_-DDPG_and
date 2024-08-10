## Solving an Optimization Problem in an Active RISAssisted ISAC System Using DRL Algorithms (DDPG and SAC).

This project focuses on solving an optimization problem in an active Reconfigurable Intelligent
Surface (RIS)-assisted Integrated Sensing and Communication (ISAC) system using Deep
Reinforcement Learning (DRL) algorithms. 

![BEAM](https://github.com/user-attachments/assets/e35f620d-5933-4bf4-8f00-beff79822c89)

The goal is to maximize the dual-function radar
sensing base station (DFRC BS) by jointly optimizing the beamforming matrix 𝑊 W of the base
station and the reflection phase shift matrix of the active RIS, all while ensuring the Signal-toInterference-plus-Noise Ratio (SINR) of the communication user is maintained. The project
employs DRL algorithms, specifically Deep Deterministic Policy Gradient (DDPG) and Soft
Actor-Critic (SAC), to achieve the optimization. It involves creating a custom environment in
OpenAI Gym, integrating it with Stable Baselines3 for training the DRL models, and comparing
the performance and convergence of ordinary DDPG, double DDPG, and SAC algorithms
through simulation and graphical analysis. The outcome of this project aims to enhance the
efficiency and performance of ISAC systems in modern wireless communication networks.

![image](https://github.com/user-attachments/assets/56c00889-cbba-461c-b0cc-03b13bbee5f2)
