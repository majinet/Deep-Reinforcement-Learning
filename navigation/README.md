# Navigation

## Project Details

For this project, I will train an agent to navigate (and collect bananas!) in a large, square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.

### Environment Details

This project is run on Unity ML-Agents Simulator. You need to install [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) in your local machine.

- Number of agents: 1
- Number of Actions: 4 (move forward, move backward, left, right)
- Number of States: 37

### Getting Started

The code are written in Pytorch and Python 3. The following softwares are required;
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
- Pytorch
- Python 3
- Numpy
- Cuda 8 (Optional) if you want to run on GPU

### Instructions

To train and run Navigation, Download the all files in navigation folder

After download, open Jupyter notebook and follow steps for training and run Reacher.
- Navigation.ipynb for DDPG version.

### Results

[Navigation report](Report.pdf)

### References
1. [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/pdf/1312.5602.pdf)
2. Sample code of Deep Q Network in Nanodegree program.


