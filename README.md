# Project 1: Navigation

### Introduction

This repo is for an agent that is able to navigate its world and collecting tasty yellow bananas, while avoiding sour blue bananas! 

It has been solved as part of Udacity's [Deep Reinforcement Learning](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) Nanodegree program in April 2020.

### Setting 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, an agent must get an average score of +13 over 100 consecutive episodes.

### Install dependencies

The `Pipfile` in this project specifies all dependencies that are needed. Please consult it in order to get the project working. 

In order to run the Jupyter Notebook `Navigation.ipynb`, please see the installation instructions [here](https://jupyter.readthedocs.io/en/latest/install.html). 

To run the notebook, you also have to download the `Banana` environment from Udacity's [project page](https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation). If your system is not Linux, please adjust the respective line of code in the beginning of `Navigation.ipynb` to point to your environment.


