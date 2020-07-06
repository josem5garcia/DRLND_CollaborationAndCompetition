# DRLND_CollaborationAndCompetition
Third project of the Deep Reinforcement Learning Nano Degree

## Introduction

This repository contains all the files required in the project 'Collaboration and Competition', from the Deep Reinforcement Learning Nano Degree, including all the code to run the model, and a report with the results obtained.

This project make use of the Unity environment, and creates a Multi-Agent Deep Deterministic Policy Gradient (MADDPG) agent to solve the problem implemented in Python 3 with PyTorch.

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
- This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## How to run the agent
In order to do this, it is just necesary to run the file 'project.ipynb', or open the Unity ML Agent with the weights included in the repository (already trained agent).

## Installing what is required
1. Install Unity (https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
2. Download the Unity ML environment and unzip the file (it must be pasted in the root folder).
3. Create Conda Environment with Python 3.6
4. Install Dependencies (python folder)
