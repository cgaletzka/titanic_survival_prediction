# titanic_survival_prediction
This repository contains a short machine learning workflow in Jupyter Notebook for the Kaggle competition "Titanic: Machine Learning from Disaster".

## Objective
Predict passenger survival based on passenger information (e.g., age, passenger class) using supervised learning.

## Approach
- Feature engineering (e.g., title, family size)
- Preprocessing using scikit-learn Pipelines
- Tuning logistic regression model (C-parameter)
- Feature selection via regularization (L1 penalty)
- Comparison to other models  (XG and random tree classifiers)

## Results
Logistic regression:
- *Cross-validated accuracy: ~0.82*
- *Kaggle leaderboard accuracy: ~0.78*
