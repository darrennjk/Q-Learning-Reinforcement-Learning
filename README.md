# Balancing a Pole on a Cart using Q-learning
## 23S2 SC3000 Assignment 1
This project is an implementation of reinforcement learning (RL) on the classic control problem, CartPole. The objective of the game is to balance a pole on a cart that moves along a frictionless track, using only two possible actions: move the cart left or right. The goal of the RL agent is to maximize the cumulative reward obtained over time by choosing the best action at each state. We use the Q-learning algorithm to train the agent, and evaluate its performance by measuring the total reward obtained over a certain number of episodes. The code is implemented in Python and utilizes OpenAI Gym environment for simulation. This project showcases the application of RL algorithms in solving complex control problems and demonstrates the ability of machine learning models to learn from their environment and improve their decision-making capabilities.

## Team Name: RL Enjoyers

## Team Members
- Clement Tan Kang Hao
- Darren Ng Joon Kai
- Denzyl David Peh

## Team Contribution

#### Training the RL Agent
- Discretizatisation of states - Clement, Darren
- returnIndexState() - Denzyl
- selectAction() - Clement
- simulateEpisodes() - Darren, Denzyl, Clement

#### Task 1: Development of RL Agent
- Sampling of random state from the CartPole Environment - Darren

#### Task 2: Demonstrate the effectiveness of the RL agent
- Running 100 episodes of the RL agent - Denzyl
- Plotting cumulative reward against episodes using Matplotlib - Darren
- Calculation of average reward over the 100 episodes - Clement

#### Task 3: Render one episode played by the developed RL agent on Jupyter
- Rendering video of an episode of our trained RL agent - Darren

#### Task 4: Format the Jupyter notebook
- Writing of step-by-step instructions and explanations - Clement, Darren, Denzyl

## References
- Detailed Explanation and Python Implementation of Q-Learning Algorithm in OpenAI Gym (Cart-Pole) - https://www.youtube.com/watch?v=KMjQmG5Uzis
- Q Learning In Reinforcement Learning | Q Learning Example | Machine Learning Tutorial | Simplilearn - https://www.youtube.com/watch?v=tMnc-hhO2jE
- Detailed Explanation and Python Implementation of the Q-Learning Algorithm with Tests in Cart Pole OpenAI Gym Environment – Reinforcement Learning Tutorial - https://aleksandarhaber.com/q-learning-in-python-with-tests-in-cart-pole-openai-gym-environment-reinforcement-learning-tutorial/
- Sample codes from Problem Description

