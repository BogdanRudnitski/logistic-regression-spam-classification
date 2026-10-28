# Logistic Regression Model for Spam Email Classification

Academic machine learning project for **COMP 551 - Applied Machine Learning** at McGill University.

Implemented and evaluated logistic regression models for binary email spam classification using the UCI Spambase dataset.

## Project Overview

- **Logistic Regression:** Implemented a binary classifier from scratch using NumPy, mini-batch stochastic gradient descent, cross-entropy loss, and L2 regularization.
- **Hyperparameter Tuning:** Used 10-fold cross-validation to evaluate learning rates, batch sizes, training epochs, and weight initialization methods.
- **L2 Regularization:** Studied the impact of regularization strength on training and validation performance, including the bias–variance trade-off.
- **L1 Regularization:** Used scikit-learn to analyze coefficient paths, feature sparsity, and cross-validation accuracy across regularization strengths.

## Results

- **90.04% test accuracy** using the tuned L2-regularized model.
- **93.48% mean cross-validation accuracy** for the best L1 configuration.
- Evaluated model performance through accuracy, cross-entropy loss, and visualizations of training behavior and regularization effects.

## Technologies

Python, NumPy, Pandas, Matplotlib, scikit-learn, Jupyter Notebook

## Files

- [Jupyter Notebook](spam_classification.ipynb) – Implementation, experiments, and visualizations.
- [Project Report](report.pdf) – Methodology, results, and discussion.

## Contributors

Bogdan Rudnitski, Olivier Ren, Maxim Qu
