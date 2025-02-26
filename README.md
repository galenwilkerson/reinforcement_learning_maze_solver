# Reinforcement Learning Maze Solver

![Gridworld Training Animation](https://github.com/galenwilkerson/galenwilkerson.github.io/blob/master/gridworld_training.gif)

This repository demonstrates a simple **reinforcement learning** approach to navigating a randomly generated maze (a “GridWorld”). The agent must learn to move from a start cell to a goal cell while avoiding blocked cells and incurring small step penalties.

## Overview
- **Notebook**: [Gridworld Maze Navigation.ipynb](https://github.com/galenwilkerson/reinforcement_learning_maze_solver/blob/main/Gridworld%20Maze%20Navigation.ipynb)
- **Method**: Q-learning
- **Environment**: Random obstacles, random start and goal cells

## How It Works
1. **Initialize** a grid with obstacles (gray), a start cell (blue), and a goal cell (green).
2. **Agent** (red dot) can move up/down/left/right each step.
3. **Rewards**:
   - **+1** upon reaching the goal  
   - **-0.01** each step to encourage efficient paths  
4. **Q-learning** updates a Q-table of **(state, action)** pairs to estimate the long-term reward for each action in each cell.

## Running the Notebook
1. Clone this repository or download the notebook directly.
2. Make sure you have Python 3.7+
