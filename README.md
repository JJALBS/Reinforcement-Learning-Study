# Reinforcement Learning Study

This repository contains Jupyter notebooks documenting my study of foundational reinforcement learning algorithms.

## Contents

### `DQN.ipynb`

This notebook includes:

1. A vanilla implementation of the DQN algorithm.
2. The PyTorch example version of DQN.

### `Actor_Critic.ipynb`

This notebook includes:

1. REINFORCE
2. A2C
3. PPO

These algorithms are implemented as vanilla versions, except that the policy update direction is normalised.

## Environment Setup

This project uses a Conda environment specified in `environment.yml`.
From the project root directory, run:
```bash
conda env create -f environment.yml
