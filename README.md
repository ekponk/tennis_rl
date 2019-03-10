## Collaboration and Competition Reinforcement Learning Project

This is an example of Deep Deterministic Policy Gradient reinformcement learning in a simple game environment with multiple agents.
The goal is to train two agents to play tennis together, with longer play sessions getting higher rewards.

Some pre-trained model weights are provided. A GPU is preferred for training.

For more information, please see the introduction to the original github project [here] ( https://github.com/udacity/deep-reinforcement-learning/tree/master/p3_collab-compet ).

## Environment

This is an example of an Actor-Critic Deep Reinforcement Learning method in a simple game environment.
The goal is to get two agents to play tennis.

The environment is provided as a custom Unity project from Udacity, found here in the `Tennis_Linux` folder.
The original Linux environment can be downloaded [here] (https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip).

The environment has 24 states. 
Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

## Manifest


File | Description
------------------|-------------------
tennis_project.ipynb | Main ipython file
Tennis_Linux | Unity code repository
ddpg_agent.py | Learning agent
model.py | PyTorch network model
checkpoint_my_actor.pth | Actor weights
checkpoint_my_critic.pth | Critic weights
install.sh | Installation
requirements.txt | Necessary modules
report.md | Report on the project
training.png | Image
README.md | This file


## Installation

1. Clone the assocated repository
2. Run the install.sh file `source install.sh`
3. `jupyter-notebook continuous_project.ipynb`
4. Follow the instructions in the notebook 







