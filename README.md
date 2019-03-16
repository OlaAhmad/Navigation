[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

This project trains a DQN agent to navigate in a large square enviornment to collect yellow bananas while avoiding blue bananas. 

![Trained Agent][image1]

The envioenment contains yellow and blue bananas; during training the agent gets reward = +1 if succesfully collected a yellow banana and a reward = -1 if collected a blue banana.

### Getting started

Download the Navigation repository from the top-right button. You can also clone the repository and downloaded from a terminal in your workspace directory using the following command line:
    
    git clone https://github.com/OlaAhmad/Navigation.git
        
### Usage

Go to the Navigation folder and open the Navigation notebook to train the DQN agent as follows:

    cd Navigation
    Jupyter notebook Navigation.ipynb

When runing the notebook, the agent will start training over a number of episodes; it will stop when the episodes get finished or if the average score gets bigger than 16. If so, the trained model will be saved in "model.pth" 
### Codes

In this repository we adapted two python codes that used when running the notebook to train the dqn agent: 
1. model.py: builds the Q-Network to model the action policy. 
2. dqn_agent.py: interacts with Banana enviornement and learns the agent from it.

### Resources

* udacity/deep-reinforcement-learning
