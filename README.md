# drln_navigation
Navigation project for UDACITY course Deep Reinforcement Learning


## Project Details
An agent is trained to navigate and collect bananas in a large, square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas. 

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started
UDACITY workspace was used for the project. The environment uses Python 3.6. The following pip libraries are needed:
- torch: 0.4.0
- numpy: 1.12.1
- unityagents

Optional: if not running on workspace, clone the DRLND repo https://github.com/udacity/deep-reinforcement-learning#dependencies, install dependencies and download the Unity Environment.

## Instructions
Open Navigation.ipynb and run all cells one by one. The notebook imports the class of Agent from agent.py. 

The function dqn() will start the training of the agent. It will end once mean reward over 100 episodes reaches at least 13 or the maximum number of total episodes (n_episodes).
