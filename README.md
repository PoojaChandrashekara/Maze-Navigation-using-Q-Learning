
# Maze Navigation using Q-Learning

This repository implements a Q-Learning agent to navigate a complex maze environment, aiming to reach the goal state while maximizing rewards and avoiding obstacles.

## Project Description

This project showcases the application of Q-Learning, a popular reinforcement learning algorithm, in solving a maze navigation problem. The agent interacts with the maze environment, learning from its experiences to choose optimal actions that lead to the goal state efficiently.

## Key Features

1. Maze Environment:
 Customizable maze structure using a 2D list representation.
2. Defined start and goal states.
 Rewards associated with different cell types (goal, obstacles, bonuses, penalties).
3. Q-Learning Agent:
 - Learns a Q-value table to estimate the expected future reward for taking an action in a given state.
 - Employs an epsilon-greedy strategy to balance exploration and exploitation during learning.
 - Trains over multiple episodes to refine its policy.
4. Visualization:
 - Plots the accumulated rewards over training episodes to illustrate learning progress.
 - Visually depicts the optimal path discovered by the agent within the maze.

## Installation

- Clone the repository

  ```bash
  git clone https://github.com/PoojaChandrashekara/Maze-Navigation-using-Q-Learning.git

- Install dependencies:

  ```bash
  pip install numpy matplotlib

- Use code with caution.

## Usage

- Run the code to train the agent and visualize the results.
- Use code with caution.

## Customization

- Modify the maze_data variable in maze_qlearning.ipynb to define your custom maze layout.
- Adjust reward values and other parameters in the Maze and QLearningAgent classes to fine-tune the agent's behavior.

## Additional Information

- Algorithm: Q-Learning
- Environment: Maze environment
- Dependencies: numpy, matplotlib
- Author: Pooja Chandrashekara
- License: MIT License
