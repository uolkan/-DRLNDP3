# -DRLNDP3

Collaboration and Competition
# About this project

This repository of DeepRL source code is work of 3rd Project - Collaboration and Competition in 
**[Udacity Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)**

For this project, we work with the Tennis environment which is created by using Unity ML-Agents([github repository](https://github.com/Unity-Technologies/ml-agents))


# Project Details

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). 
Specifically, after each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

# Getting Started
After downloading the project files; create an environment from [Environment](./environment.yml) then follow the instructions.

Note: Additionally Unity ML-Agents to be installed by following instructions ([github repository](https://github.com/Unity-Technologies/ml-agents))
 
# Instructions
To train the agent, start jupyter notebook, open - [`Tennis.ipynb`]( ./Tennis.ipynb)
and execute! For more information, please check instructions inside the notebook.

# Report
You can read the report to understand the implemented algorithm and hyperparameters better. 
- [Report]( ./Report.pdf)

Important Note: All images and charts (except the plot of rewards) in report are from Udacity lecture notes. 


You can watch the training agent and trained agent videos at below links; 

Without Training: 
https://youtu.be/5B2y8rOncAE
Training :
https://youtu.be/gs503f_Kn48
Smart Agent: 
https://youtu.be/Y93H6IBCpM0
