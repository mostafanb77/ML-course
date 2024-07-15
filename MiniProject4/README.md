# ML_4022_MP4
# Project Title: Mini Project 4: Reinforcement Learning
## Overview
Completed for the KNTU class of Dr. Aliyari
<br/>Focuses on reinforcement learning in a grid-based environment
<br/>Implements Q-Learning and Deep Q-Network (DQN) algorithms
## Project Description
4x4 grid environment
<br/>Agent seeks gold while avoiding pits and a Wumpus
<br/>Actions: Move and shoot in four directions
<br/>Rewards: +100 for finding gold, -1000 for falling into pits or encountering Wumpus, +50 for shooting Wumpus, -1 for movement
## Q-Learning
Off-policy algorithm to learn optimal policy directly
<br/>Epsilon-greedy policy for exploration and exploitation balance
<br/>Training process involves Q-table updates based on state transitions
## Deep Q-Network (DQN)
Neural network approximates Q-values
<br/>Architecture: Input layer, two hidden layers (128 neurons each, ReLU activation), output layer
<br/>Uses replay memory for training stability
## Comparison of Q-Learning and DQN
Cumulative Rewards: Plot to visualize performance over episodes
<br/>Average Reward per Episode: Compare after 1000 episodes to evaluate algorithm effectiveness
<br/>Results: Discuss performance differences between Q-Learning and DQN
## Environment Details
Implemented in GridEnvironment class
<br/>Includes grid layout, agent starting position, goal, pits, Wumpus, and actions
<br/>Specific rewards and penalties defined based on agent's interactions
## Google Drive
Here's the google drive link :
https://drive.google.com/drive/folders/1XbRTelv7H89gzgOneYiqfahZuOEStQlz?usp=sharing
## Contact
For any questions or comments, please contact us at:

mostafa.nabipour1@gmail.com
