# Reinforcement Learning Algorithms

This repository contains implementations of various reinforcement learning algorithms, organized by different approaches and techniques.

## Repository Structure

```
.
├── hierarchical_reinforcement_learning/
│   ├── smdp_intra_qlearning_code.ipynb
│   └── smdp_intra_qlearning_report.pdf
├── multi_armed_bandits/
│   └── epsilon_greedy_ucb.ipynb
└── td_control_methods/
    └── sarsa_qlearning.ipynb
```

## Contents

### Hierarchical Reinforcement Learning

* **SMDP and Intra-Option Q-Learning**

  * `smdp_intra_qlearning_code.ipynb`: Jupyter Notebook implementing SMDP and intra-option Q-learning algorithms within the Gymnasium Taxi-v3 environment.
  * `smdp_intra_qlearning_report.pdf`: A detailed report outlining the problem setup and providing a comparative analysis of the implemented algorithms.

### Multi-Armed Bandits

* **Exploration Strategies in Bandit Problems**

  * `epsilon_greedy_ucb.ipynb`: Implementation and comparative study of two fundamental exploration strategies for multi-armed bandits:

    * *Epsilon-Greedy*
    * *Upper Confidence Bound (UCB)*

### Temporal-Difference Control Methods

* **Classic TD Control Algorithms**

  * `sarsa_qlearning.ipynb`: Jupyter Notebook implementing and analyzing two widely used temporal-difference control algorithms in a configurable grid world environment:

    * *SARSA*
    * *Q-Learning*

## Usage
Navigate to the specific algorithm directory and open the Jupyter notebook in Google Colab.
