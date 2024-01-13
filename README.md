# FrozenLake8x8-DQL

FrozenLake8x8-DQL is an improved reinforcement learning project that applies Deep Q-Learning to the FrozenLake 8x8 environment using PyTorch. The project utilizes a neural network to learn a policy that allows an agent to successfully navigate the larger FrozenLake map.

<!-- Resized GIF with equal height and width -->
<p align="center">
  <img src="https://github.com/hemantkrishnan4/FrozenLake8x8-DQL/assets/96692095/98380e05-db26-491c-a33f-6f2082fec5bf" width="50%" height="50%">
</p>


## Training Result
<p align="center">
  <img src="https://github.com/hemantkrishnan4/FrozenLake8x8-DQL/assets/96692095/6788662d-ae87-4aab-acf7-e5bc2d3a1bc0" alt="frozen_lake_8x8_Training Result">
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

