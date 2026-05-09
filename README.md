# Resource Estimation for 5G Sliced Network Using DRL

## Overview
This project presents a Deep Reinforcement Learning (DRL)-based framework for intelligent Resource Block (RB) estimation in 5G sliced networks. The proposed system dynamically allocates RBs based on QoS requirements and traffic conditions for different network slices including eMBB, URLLC, and mMTC.

The implementation uses:
- Deep Deterministic Policy Gradient (DDPG)
- Deep Q-Network (DQN)
- MATLAB Reinforcement Learning Toolbox

The proposed DRL framework improves resource utilization, reduces latency, and enables adaptive slice-aware RB allocation compared to conventional rule-based methods.

## Network Slice Types
 eMBB -> Enhanced Mobile Broadband 
 URLLC -> Ultra-Reliable Low Latency Communication
 mMTC -> Massive Machine-Type Communication

## Technologies Used
- MATLAB R2023b
- Reinforcement Learning Toolbox
- Deep Learning Toolbox
- DDPG
- DQN
- 5G Network Slicing
- 
## Dataset Features
- Packet Loss Rate (Reliability)
- Packet Delay Budget (Latency)
- GBR
- Use Case Type
- UE Category
- Technology Supported
- Slice Type
- 
## Workflow
1. Load and preprocess dataset
2. Perform network slicing
3. Create custom RL environment
4. Train DQN and DDPG agents
5. Estimate Resource Blocks dynamically
6. Compare DRL allocation with rule-based methods
7. Generate performance visualizations

## Results

### DQN Training Progress
[DQN Training](Results/Training-Progress-of-DQN agent .jpeg)

### DDPG Training Progress
[DDPG Training](Results/DDPG Agent- Trainig Progress.jpeg)

### Overall RB Allocation Comparison
[RB Comparison](Results/Overall-Estimated-RB's-DDPG.jpeg)

### RB Allocation Per Slice
[RB Allocation](Results/RB's-Allocation-Per-slice.jpeg)

### Distribution of Estimated Resource Blocks
[RB Distribution](Results/DiStribution-of-estimated-Resource-Blocks-DQN Agent.jpeg)

## Key Outcomes
- Intelligent dynamic RB estimation achieved using DRL
- Slice-aware allocation for eMBB, URLLC, and mMTC
- Improved QoS-aware resource management
- Stable reward convergence using DDPG and DQN agents
- Adaptive RB allocation based on traffic conditions

## Author
Pradeep S  
M.Tech – Digital Communication Engineering  
BMS College of Engineering, Bengaluru
