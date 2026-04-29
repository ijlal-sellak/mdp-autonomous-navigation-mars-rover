# Mars Rover MDP Navigation
<img width="986" height="549" alt="image" src="https://github.com/user-attachments/assets/da576e5f-98d4-4b75-a5d2-08fcb47cb14c" />
<img width="1365" height="521" alt="image" src="https://github.com/user-attachments/assets/21c40c72-178c-4ebd-a2a6-946828c2e131" />


Autonomous Mars rover navigation using **Markov Decision Processes (MDP)** and **value iteration** in a stochastic grid-based environment.

## Problem Statement

Autonomous navigation is a critical challenge for planetary rovers operating in uncertain and hazardous environments.
The rover must reach a target location while avoiding obstacles and minimizing navigation cost, despite uncertainty in action outcomes.


## Why Markov Decision Processes (MDP)?

Classical pathfinding algorithms assume deterministic environments.
However, real autonomous systems operate under uncertainty.

MDPs provide a formal framework to model:
- States (rover positions)
- Actions (movements)
- Transition probabilities (uncertain outcomes)
- Rewards (goal-reaching and penalties)

This allows the computation of an **optimal policy** that maximizes long-term expected reward.
## Results

The MDP-based policy successfully guides the rover to the goal while avoiding obstacles.
Future updates will include performance metrics and comparisons with baseline strategies.


## Limitations & Future Work

- Assumes full observability of the environment
- Static obstacles only
- Known transition probabilities

Future improvements may include:
- Partial observability (POMDP)
- Dynamic environments
- Learning-based approaches (Reinforcement Learning)


## Technologies

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

