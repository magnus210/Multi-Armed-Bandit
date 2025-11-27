# Multi-Armed Bandit - Epsilon Greedy

This project demonstrates the Multi-Armed Bandit problem using the epsilon-greedy algorithm, implemented in Python.

## Overview

The Multi-Armed Bandit problem is a foundational example in reinforcement learning. It involves multiple slot machines (arms), each with an unknown reward distribution. The agent aims to maximize its total reward by balancing:

- **Exploration:** Testing different arms to discover their rewards.
- **Exploitation:** Selecting the arm that currently seems best.

The *epsilon-greedy* strategy does this by picking a random arm with probability ε (exploration) and otherwise choosing the arm with the highest estimated value (exploitation).

## Features

- **Bandit class**: Models multiple arms with random reward distributions.
- **Simulation**: Compares epsilon values (0, 0.01, 0.1) over multiple runs and steps.
- **Statistics tracked**: Average reward per step, percentage of optimal action selections.
- **Visualization**: Plots show the effect of epsilon on learning speed and exploitation vs. exploration.

## Usage

1. Install Python and required packages (`numpy`, `matplotlib`).
2. Open and run the provided notebook `MLB-EG.ipynb`.
3. Analyze visualizations to see how different ε values affect performance.

## Main Sections

- Initialization of bandit problem and epsilon values.
- Simulation loop for multiple runs and steps.
- Tracking and plotting:
  - Average reward per step.
  - Percentage of optimal action selections.
- Comparison of performance for different epsilon values.

## Example Visualization

- **Average reward** vs. steps for each epsilon.
- **% Optimal action** vs. steps for each epsilon.

## References

- Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction*.
- [Wikipedia: Multi-Armed Bandit](https://en.wikipedia.org/wiki/Multi-armed_bandit)
