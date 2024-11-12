# Hyperparameter Optimization of DQN Using GAs
 The data was generated during the hyperparameter optimization of the Deep Q-Learning (DQN) algorithm in the CartPole environment, using genetic algorithms to select the best configurations for selection, crossover, and mutation, which impact the model's effectiveness.

Each file contains a unique name representing the selection_crossover_mutation.csv configuration under which it was generated. The files contain 3,200 records, each representing an individual across successive generations for the given genetic algorithm.

- The first column represents the GA iteration number.
- The second column contains information about the optimized hyperparameters and their values.
- The third column provides the agent's performance for the given configuration.
- The fourth column shows the highest score achieved in a specific generation.

Summing all datasets, there are 76,800 records, with each record corresponding to a set of hyperparameters and the agent's performance in the CartPole environment over the last 50 episodes of training out of a total of 150 training episodes.
