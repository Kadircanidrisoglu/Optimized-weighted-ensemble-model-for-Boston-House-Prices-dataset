# Regression Model Comparison and Weighted Ensemble Optimization

This notebook compares the performance of various regression models, including shallow neural network model, tree-based models, and linear model, using the Boston House Prices dataset. The main focus of this project is not to create the best individual model but to explore how different types of models perform on the same regression task.

## Key Highlights:

- **Model Types Evaluated:**
  - Shallow Neural Network Model
  - Tree-based Models (Random Forest, Decision Tree)
  - Linear Model (Linear Regression)

- **Weighted Ensemble Model:**
  - A custom weight optimization algorithm was developed to create an ensemble model by combining predictions from the individual models.
  - This algorithm optimizes the weights assigned to each model to minimize prediction error.
  - The weighted ensemble model with optimized weights outperformed all individual models in terms of overall performance.

## Objective:

The primary objective of this project is to investigate the performance of various models on a regression problem and demonstrate how a well-optimized ensemble can yield superior results compared to individual models.
