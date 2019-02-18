# Udacity_DeepRL_ContinuousControl

Implementation of the second project at the Deep Q-learning to the Unity ML-Agent. Unity Machine Learning Agents (ML-Agents) is an open-source Unity plugin that enables games and simulations to serve as environments for training intelligent agents. For this project, the [Reacher](https://https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment is used.

## Project Details

In the Reacher environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.


## Getting Started

Follow the instructions in the DRLND GitHub repository to set up the Python environment [here](https://github.com/udacity/deep-reinforcement-learning#dependencies). 

Additionally, install PyTorch (the project utilized PyTorch ver 0.4.0). 

## Instructions

Run the `Continuous_Control.ipynb` in order to observe the performance of the random policy of the agent as well as the performance of the smart agent.
