# Continuous Control

## Project Details

In this Reacher environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Environment Details

This project is run on Unity ML-Agents Simulator. You need to install [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) in your local machine.

- Number of Visual Observations (per agent): 0
- Vector Observation space type:             continuous
- Vector Observation space size (per agent): 33
- Number of stacked Vector Observation:      1
- Vector Action space type:                  continuous
- Vector Action space size (per agent):      4

### Getting Started

The code are written in Pytorch and Python 3. The following softwares are required;
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
- Pytorch
- Python 3
- Numpy
- Cuda 8 (Optional) if you want to run on GPU

### Instructions

To train and run Reacher. Download the all files in continuous-control folder

After download, open Jupyter notebook and follow steps for training and run Reacher.
- Continuous_Control_highreward.ipynb for DDPG enhancement version.
- Continuous_Control.ipynb for DDPG version.

### References
1. [ontinuous control with deep reinforcement learning](https://arxiv.org/pdf/1509.02971.pdf)

