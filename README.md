# continuous-control-DDPG
Udacity deep learning continuous control project

</br>

## Project details
This project uses Reacher Unity environment. In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.

</br>

## Getting started
The project uses Jupyter Notebook.
This command needs to be run to install the needed packages:

```
!pip -q install ./python
```
Running all the cells in the notebook will install it automatically.

</br>

## Instructions
The project consists of 8 files:
* ContinuousControlProject.ipynb - run this file in Jupyter Notebook
* agent.py - the DDPG Agent class
* network.py - the Actor and Critic models
* memory.py - the replay buffer class
* noise.py - the noise class
* config.py - the configuration class
* checkpoint_critic.pth - critic trained model
* checkpoint_actor.pth - actor trained model
* Report.md - description of the implementation

Use Config() class to define all project configurations (hyperparameters, network, optimizers etc.)
