# Educational Informer Implementation

This project is an educational implementation of the Informer model for time series forecasting.

## Project Learnings

*   Understand the Informer architecture
*   Understand Probsparse Attention
*   Learn how to implement time series models in PyTorch.
*   Gain practical experience with hyperparameter tuning using Optuna.
*   Address overfitting challenges in deep learning models.

## Problem Addressed

The initial implementation exhibited a strong tendency to overfit the training data. This was evident from observing a very low training loss while the validation loss remained high.

## Solution: Hyperparameter Tuning with Optuna

To mitigate overfitting and find optimal model configurations, [Optuna], a hyperparameter optimization framework is used. Optuna systematically explores different hyperparameter combinations to identify settings that improve generalization performance (i.e., lower validation loss).




