# Anti-cancer Activity Prediction

This repository contains the code, data, and documentation for the Anti-cancer Activity Prediction competition. The competition focuses on predicting the anti-cancer activity of chemical compounds using graph representations.

## Dataset

The dataset consists of chemical compounds represented as graphs, where atoms are nodes and bonds are edges. Each compound is labeled as positive or negative against non-small cell lung cancer.

## Experimental Protocol

The experimental protocol follows a data science life-cycle approach. The provided code template contains detailed comments explaining each line of code. The code encompasses data preprocessing, model training, and evaluation. Hyperparameters are tuned by modifying their values and observing the impact on model performance. The search space for hyperparameter tuning depends on the chosen model and includes various configurations such as different feature sets, preprocessing techniques, and model architectures.

## Problem Formulation

The problem involves predicting the anti-cancer activity of chemical compounds based on their graph representations. The input is a set of chemical compounds represented as graphs, with atoms and bonds as nodes and edges, respectively. The output is a binary classification indicating whether a compound is positive against non-small cell lung cancer or negative. The data mining function required is classification. Challenges may include handling unbalanced datasets, determining the optimal graph convolution mechanisms, and ensuring the model generalizes well to unseen compounds. The impact of accurate anti-cancer activity prediction can contribute to drug discovery and development.

## Model Tuning and Documentation

Based on the provided template, the goal is to improve the model's performance on the public leaderboard by following the data science life-cycle for tuning. This involves trying different features, hyperparameters, preprocessing techniques, and even exploring different model architectures. Each trial should be well-documented, including the rationale behind the changes made, the expected outcome, and the observed performance. It is important to document the thought process to aid in understanding and troubleshooting. The notebook should be organized by listing thoughts and observations for each trial, followed by the corresponding code.

### Trials

You are required to tune the model at least 10 times. The tried solutions should cover different feature sets, preprocessing techniques, and model configurations. Specifically, you should:

1. Experiment with at least three graph convolution aggregation mechanisms (message passing mechanisms) used in the graph convolution layer. Explain your understanding of the chosen mechanisms based on the documentation/paper.
2. Implement up-sampling techniques to address the highly unbalanced dataset, especially to increase the number of positive class samples.


