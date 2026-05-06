# Machine Learning: Wine Quality Classification

Final coursework for the Machine Learning module (University of London 
Data Science & AI programme).

## Project

Binary classification task on the UCI Wine Quality dataset (red wine). 
Wines with quality scores >= 6 classified as "good quality"; below 6 
as "not good quality". Trained and compared three model classes 
including supervised and unsupervised approaches.

## Models compared

- Logistic Regression — baseline linear classifier (accuracy: 74%)
- Random Forest — ensemble method, best performer (accuracy: 81.6%, F1: 0.825)
- Neural Network (MLP Classifier) — deep model, competitive but below Random Forest (accuracy: 78.7%, F1: 0.80)
  
## Approach

- Exploratory data analysis on 11 physicochemical features
- Stratified train/test split with StandardScaler normalisation
- Model evaluation with classification metrics
- Self-directed research extension for additional marks

## Key finding

Random Forest outperformed both Logistic Regression and Neural Network 
on structured tabular data, confirming that wine quality prediction 
depends on nonlinear interactions between physicochemical features. 
Neural networks underperformed likely due to small dataset size (1,599 
rows) and sensitivity to hyperparameter tuning.

## Stack

Python · scikit-learn · pandas · NumPy · Matplotlib · Jupyter

## Dataset

UCI Machine Learning Repository — Wine Quality (Red Wine)
Cortez et al. (2009): https://archive.ics.uci.edu/ml/datasets/Wine+Quality
