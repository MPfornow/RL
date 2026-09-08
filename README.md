# Hugging Face Deep Reinforcement Learning — Revised Code

This repository contains my revised and updated implementations of the exercises and projects from the [Hugging Face Deep Reinforcement Learning Course](https://huggingface.co/learn/deep-rl-course/unit0/introduction).

The notebooks are based on the original course material, with modifications, corrections, and updated setup instructions where needed to work with newer versions of libraries and environments.

## Course Units

- [Unit 1 — Introduction to Deep Reinforcement Learning](notebooks/unit1/unit1.ipynb)
- [Unit 2 — Q-Learning](notebooks/unit2/unit2.ipynb)
- [Unit 3 — Deep Q-Learning](notebooks/unit3/unit3.ipynb)
- [Unit 4 — Policy Gradient Methods](notebooks/unit4/unit4.ipynb)
- [Unit 5 — Unity ML-Agents](notebooks/unit5/unit5.ipynb)
- [Unit 6 — Actor-Critic Methods](notebooks/unit6/unit6.ipynb)
- [Unit 7 — Multi-Agent Reinforcement Learning](notebooks/unit7/unit7.ipynb)

## Why Revised?

Some commands, dependencies, and APIs in the original course material can become outdated as the underlying libraries and environments evolve.

These notebooks document the changes I made while following the course, including updated code and environment setup where necessary.

The goal is to make the course exercises easier to reproduce with more recent software versions.

## Unit 7 — Multi-Agent Reinforcement Learning

Unit 7 uses Unity ML-Agents and the SoccerTwos environment to demonstrate multi-agent reinforcement learning and self-play.

The original course setup may require modifications because of changes in ML-Agents and its dependencies.

The Unit 7 notebook therefore includes an updated local setup and revised commands used to run the environment.

> **Note:** The SoccerTwos training environment requires significant computational time. The Unit 7 notebook is intended to be run locally rather than in Google Colab for the full training process.

## Environment and Compatibility

The exact versions and setup may vary as the underlying libraries continue to change.

For Unit 7, the local setup currently uses:

- Python 3.10.12
- Unity ML-Agents
- ML-Agents Environments
- PyTorch
- CUDA-enabled GPU training
- Unity SoccerTwos environment

The notebooks document the setup used when the corresponding unit was completed.

## Disclaimer

This is an independent revision of the Hugging Face Deep Reinforcement Learning Course material.

The original course content and intellectual property belong to their respective authors and organizations.

This repository is intended for learning and educational purposes.
