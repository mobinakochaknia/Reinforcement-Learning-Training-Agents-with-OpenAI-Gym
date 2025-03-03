# Reinforcement Learning: Training Agents with OpenAI Gym

## Overview
This notebook explores **Reinforcement Learning (RL)** techniques for training agents in game environments such as `FrozenLake-v1` and `Taxi-v3`, utilizing the **Gym** library developed by OpenAI.

## Objectives
- Implement **Q-Learning** for solving RL problems.
- Train an agent to navigate through dynamic environments.
- Evaluate policy performance using reward-based metrics.

## Dependencies & Installation
Ensure you have the required libraries installed:
```bash
pip install gym numpy matplotlib
```

## Key Components
### 1️⃣ Introduction to Gym Library
- **Environment Setup**: Initializing tasks using `gym.make()`.
- **Agent-Environment Interaction**: Executing actions and receiving feedback.
- **Visualization**: Rendering game environments for better understanding.

### 2️⃣ Q-Learning Implementation
- **State & Action Representation**: Defining the RL agent’s decision-making framework.
- **Reward Maximization**: Optimizing agent behavior using Q-tables.
- **Exploration vs. Exploitation**: Balancing random actions and learned policies.

### 3️⃣ Performance Evaluation
- **Policy Testing**: Assessing the agent’s efficiency.
- **Reward Tracking**: Analyzing the learning progress over time.
- **Hyperparameter Tuning**: Adjusting learning rate and discount factor.

## Metadata Files
- **Stored metadata files** include training logs and Q-table updates.
- These files assist in debugging and further training refinements.

## Execution Steps
1. Install dependencies and initialize the environment.
2. Train the agent using Q-learning.
3. Evaluate the agent’s performance using test episodes.
4. Visualize learning progress and optimize the model.

## Notes
- This implementation is **Gym-based**, ensuring compatibility with standard RL frameworks.
- Training stability depends on **proper hyperparameter selection**.
- RL agents improve over multiple episodes, requiring sufficient training time.

## Author
Mobina Kochaknia (Student ID: 401106396)

