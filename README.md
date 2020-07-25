# deep_reinforcement_tennis_project
Project 3 of Udacity's Deep Reinforcement Learning nanodegree program


## Project Details
In this project, agents are trained to continously control the double-jointed robotic arm. The goal of the agents is to maintain the position at the target location for as many time steps as possible. The aim of the project is to train the agents so that they must get an average score of +30 (over 100 consecutive episodes, and over all agents).

- The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm.  
- Each action is a vector with four numbers, corresponding to torque applicable to two joints.  
- Every entry in the action vector should be a number between -1 and 1.

## Getting Started
Following libraries are required:
Python 3.x , Jupyter Notebook, NumPy, matplotlib, PyTorch, UnityEnvironment

Following are the steps for getting started with the project:  

### Step 1: Activate the Environment
Please follow the instructions in the DRLND GitHub repository's README.md to set up your Python environment. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.  

Once the environment is set, then place the file in the p2_continuous-control/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link (version 1) or this link (version 2) to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

## Instructions
Apart from the main Continous_Control_Main.ipynb file, there are following two additional files which are used in the project:
- model.py: where a neural network is defined using PyTorch and
- ddpg_agent_main: where Deep Deterministic Policy Gradients (DDPG) algorithm is defined.


