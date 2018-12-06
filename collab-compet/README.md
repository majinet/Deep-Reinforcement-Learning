# Collaboration and Competition

## Project Details

In this Tennis environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

### Environment Details

This project is run on Unity ML-Agents Simulator. You need to install [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) in your local machine.

- Number of Visual Observations (per agent): 0
- Vector Observation space type:             continuous
- Vector Observation space size (per agent): 8
- Number of stacked Vector Observation:      3
- Vector Action space type:                  continuous
- Vector Action space size (per agent):      2

### Getting Started

The code are written in Pytorch and Python 3. The following softwares are required;
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
- Pytorch
- Python 3
- Numpy
- Cuda 8 (Optional) if you want to run on GPU

### Instructions

To train and run Tennis, Download the all files in collab-compet folder

After download, open Jupyter notebook and follow steps for training and run Reacher.
- Tennis.ipynb for DDPG version.

### Results

[Collaboration and Competition report](Report.pdf)

### References
1. [Continuous control with deep reinforcement learning](https://arxiv.org/pdf/1509.02971.pdf)


