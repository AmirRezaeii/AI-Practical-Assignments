# AI Practical Assignments
This repository contains comprehensive practical assignments from an **Artificial Intelligence course**, covering classical AI techniques, search algorithms, game theory, probabilistic models, machine learning, and reinforcement learning. Each assignment is implemented as a Jupyter Notebook using Python.

The goal is to provide clear, runnable implementations of fundamental AI algorithms - from search and constraint satisfaction to neural networks and deep Q-networks.

## Search Algorithms

### Search.ipynpynb
- Classical search algorithms for problem solving
- Uninformed search: BFS (Breadth-First Search), DFS (Depth-First Search), UCS (Uniform Cost Search)
- Informed search: Greedy Best-First Search, A* search with heuristics

### Local Search.ipynb
- Optimization techniques for large state spaces
- Hill climbing (with variants: steepest ascent, stochastic)
- Simulated annealing
- Local beam search
- Genetic algorithms

### CSP.ipynb
- Constraint Satisfaction Problems
- Backtracking search
- Forward checking
- AC-3 algorithm for arc consistency
- Variable and value ordering heuristics (MRV, LCV)

## Game Theory & Adversarial Search

### Minimax.ipynb
- Minimax algorithm for two-player zero-sum games
- Alpha-beta pruning for efficiency optimization
- Evaluation function design
- Applications to games like Tic-Tac-Toe or Chess endgames

## Probabilistic Models

### Hidden Markov Model.ipynb
- HMM fundamentals: states, observations, transitions, emissions
- Forward algorithm for filtering
- Viterbi algorithm for most likely state sequence
- Applications: speech recognition, POS tagging

### Modeling Robot Navigation Using Bayesian Network.ipynb
- Bayesian networks for uncertainty reasoning
- Conditional probability tables (CPTs)
- Inference in Bayesian networks (variable elimination)
- Robot localization and navigation under uncertainty

## Machine Learning Fundamentals

### Regression.ipynb
- Linear regression for continuous prediction
- Polynomial regression for non-linear relationships
- Gradient descent optimization
- Evaluation metrics: MSE, MAE, R-squared

### Machine Learning & Classification.ipynb
- Classification algorithms: Logistic Regression, Decision Trees, k-NN
- Train-test splitting and cross-validation
- Evaluation metrics: accuracy, precision, recall, F1-score, confusion matrix
- Bias-variance tradeoff

### Neural Networks.ipynb
- Perceptron and multi-layer perceptron (MLP)
- Activation functions: sigmoid, tanh, ReLU
- Backpropagation algorithm
- Training neural networks on classification tasks

## Reinforcement Learning

### Reinforcement Learning.ipynb
- RL fundamentals: agent, environment, actions, rewards, episodes
- Exploration vs. exploitation tradeoff
- Policy evaluation and improvement

### V-Value and Q-Value Calculation.ipynb
- Value functions: V(s) for state values
- Action-value functions: Q(s,a) for state-action pairs
- Bellman equations for optimal policies
- Dynamic programming for value iteration and policy iteration

### Deep Q-Network.ipynb
- Combining deep learning with Q-learning
- Experience replay buffer for stable training
- Target network for reducing correlations
- Training DQN on environments like CartPole or Atari games

## Key Topics Covered

| Category | Techniques & Models |
|:---------|:--------------------|
| **Search Algorithms** | BFS, DFS, UCS, Greedy BFS, A*, Hill Climbing, Simulated Annealing, Genetic Algorithms |
| **Constraint Satisfaction** | Backtracking, Forward Checking, AC-3, MRV, LCV |
| **Game Theory** | Minimax, Alpha-Beta Pruning |
| **Probabilistic Models** | HMM (Forward, Viterbi), Bayesian Networks, Variable Elimination |
| **Supervised Learning** | Linear/Polynomial Regression, Logistic Regression, Decision Trees, k-NN, Neural Networks |
| **Reinforcement Learning** | Value Iteration, Policy Iteration, Q-Learning, DQN, Experience Replay |
