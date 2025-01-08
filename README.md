# RL-CartPole-DQN

This repository contains the implementation and report for the second coursework of the Reinforcement Learning (RL) module at Imperial College London. The project focuses on training a Deep Q-Network (DQN) to solve the OpenAI Gym CartPole environment, optimizing hyperparameters, and visualizing learned policies and Q-values.

## Coursework Overview

The aim of this coursework is to develop and optimize a DQN for the CartPole environment, where the goal is to balance a pole on a moving cart for as many steps as possible. Key tasks include:

1. **Hyperparameter Tuning**: Adjusting and optimizing nine standard DQN hyperparameters to improve performance.
2. **Learning Curve Analysis**: Evaluating the performance of the trained DQN through learning curves.
3. **Policy Visualization**: Visualizing slices of the learned policy in the state space.
4. **Q-Value Visualization**: Investigating the Q-values learned by the agent in different regions of the state space.

## Project Structure

- **`Coursework2.ipynb`**: The main Jupyter Notebook containing the implementation and experiments.
- **`utils.py`**: Additional utility functions and classes for DQN implementation.
- **`coursework2_report.pdf`**: The report containing detailed explanations, results, and analysis.

## Features

- **Deep Q-Network Implementation**: A PyTorch-based DQN architecture tailored for the CartPole environment.
- **Replay Buffer**: Efficient storage and sampling of transitions for training.
- **Epsilon-Greedy Policy**: Exploration-exploitation balance for training the agent.
- **Policy and Q-Value Visualization**: Tools for analyzing the learned agent's behavior.

## Requirements

The following Python packages are required to run the notebook:

- `numpy`
- `matplotlib`
- `seaborn`
- `torch`
- `gym`

To install dependencies, run:

```bash
pip install -r requirements.txt
```

## Running the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RL-CartPole-DQN.git
   cd RL-CartPole-DQN
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Coursework2.ipynb
   ```

3. Run the notebook cells sequentially to:
   - Define the DQN architecture.
   - Tune hyperparameters.
   - Train the agent.
   - Visualize the results.

## Results

- **Optimized DQN**: Successfully trained an agent to achieve an average reward exceeding 100 over multiple runs.
- **Learning Curve**: Demonstrated the agent's performance over training episodes.
- **Policy and Q-Value Insights**: Provided visualizations of the agent's decision boundaries and value estimations.

Detailed results and analyses are available in the `coursework2_report.pdf`.

## License

This project is for academic purposes and follows the coursework submission guidelines of Imperial College London. Please do not directly reuse the code for academic submissions without proper attribution.
