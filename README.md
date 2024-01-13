# FrozenLake8x8-DQL

FrozenLake8x8-DQL is an improved reinforcement learning project that applies Deep Q-Learning to the FrozenLake 8x8 environment using PyTorch. The project utilizes a neural network to learn a policy that allows an agent to successfully navigate the larger FrozenLake map.

## Training Result with Slipping On
<p align="center">
  <img src="https://github.com/hemantkrishnan4/FrozenLake8x8-DQL/assets/96692095/575ffc35-515d-4f62-a3e8-084e12ce15cb" width="50%" height="50%">
</p>

## Observation on Slippery Floor Mode

When the slippery floor mode is turned on (`is_slippery=True`), the machine learning agent is trained to navigate the FrozenLake environment with a probabilistic movement. In this mode, the agent may learn to avoid complicated paths and instead choose simpler routes to minimize the risk of slipping.

It's interesting to observe how the agent adapts its strategy when faced with the added challenge of a slippery floor. Feel free to experiment with this mode and observe the learning behavior during training.


## Training Result Grph with Slipping On
<p align="center">
  <img src="https://github.com/hemantkrishnan4/FrozenLake8x8-DQL/assets/96692095/6788662d-ae87-4aab-acf7-e5bc2d3a1bc0" alt="frozen_lake_8x8_Training Result">
</p>


## Training Result with Slipping Off
<p align="center">
  <img src="https://github.com/hemantkrishnan4/FrozenLake8x8-DQL/assets/96692095/ce050051-e224-4558-a515-690806b3c8d9" width="50%" height="50%">
</p>


## Training Result Grph with Slipping Off
<p align="center">
  <img src="https://github.com/hemantkrishnan4/FrozenLake8x8-DQL/assets/96692095/393082c9-5a0a-439e-8400-75ef87008083">
</p>

## Gymnasium Reinforcement Learning

FrozenLake8x8-DQL is part of the Gymnasium Reinforcement Learning collection, a set of Python code that solves Reinforcement Learning environments from the Gymnasium Library, formerly OpenAI’s Gym library.

## Introduction

This project extends the original FrozenLake-DQL project to the larger 8x8 environment, providing a more challenging scenario for reinforcement learning. The agent learns to make decisions by interacting with the environment, and the training process involves updating a neural network based on experiences gained during exploration.

## Prerequisites

Make sure you have the following installed before running the project:

- Python (>=3.6)
- [PyTorch](https://pytorch.org/)
- [Gym](https://gym.openai.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/FrozenLake8x8-DQL.git
   cd FrozenLake8x8-DQL
   ```

## Usage

To train the agent:
```bash
python main.py --is_training=True --render=False
```
To test the agent:
```bash
python main.py --is_training=False --render=True
```
## Acknowledgments
- Gymnasium Library
- PyTorch

Feel free to modify and enhance the project based on your needs. Happy Coding 😊

