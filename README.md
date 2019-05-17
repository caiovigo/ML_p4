# ML_p4 - Reinforcement Learning

This project was done by Caio Vigo & William Duncan.

In this repository you can find the following files:

 * Treasure_Hunters_Inc.ipynb: this is a jupyter notebook with the explanation, code and examples.
 * Treasure_Hunters_Inc.py: this is a .py defining the environment that we use in this project.
 
This project was is based on the following post https://github.com/kevlar1818/grid-world-rl

We also used the following posts as reference:
https://towardsdatascience.com/training-an-agent-to-beat-grid-world-fac8a48109a8
https://towardsdatascience.com/reinforcement-learning-with-python-8ef0242a2fa2

Finally, for details about the Reinforcement Learning idea, we used the following slides http://www.cis.upenn.edu/~cis519/fall2015/lectures/14_ReinforcementLearning.pdf

The goal of this project is to use reinforcement learning in a grid environment to avoid obstacles and reach the goal. This is done defining cost and reward functions with **Markov Decision Processes (MDP)** 

## Basic idea:

* Receive feedback in the form of rewards
* Agent’s utility is defined by the reward function
* Must (learn to) act so as to maximize expected rewards

## Grid World

* The agent lives in a grid
* Walls block the agent’s path
* The agent’s actions do not always go as planned
* Small rewards at each step
* Big rewards come at the end
* Goal: maximize sum of rewards

We will make use of **Markov Decision Processes**.

## Markov Decision Processes


* An MDP is defined by:
    * A set of states s ∈ S
    * A set of actions a ∈ A
    * A **transition function** T(s,a,s’)
    * A **reward function** R(s, a, s’)
    * A **start state** (or distribution)
    * A **terminal state**
