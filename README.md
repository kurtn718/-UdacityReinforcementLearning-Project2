# Project Details

This project uses the [Unity Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment to train an agent that has a double-jointed arm. 

A reward of +0.1 is provided for each step that the agent's hand is in the goal location.   The goal of the agent is to maintain the goal position for as long as possible.  

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1

The task is episodic, and to consider the environment solved, the agent must get an average score of +30 over 100 consecutive episodes.

# Getting Started

1. Clone this git repository on your local machine

2. Setup a Jupyter notebook on your local machine.   For details on how to do that, here is a resource that may be helpful:
https://www.dataquest.io/blog/jupyter-notebook-tutorial/

2. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.


3. Place this file in the directory that you cloned the git repositiory, and unzip (or decompress) the file. 


# Instructions

Open the Navigation.ipynb notebook file, and run the notebook to train the agent
