## Heart disease analysis
My project for learning Machine Learning in Python. It predicts the level of heart disease based on multiple features.

# Description

This project includes the following steps:

- Data preprocessing
- Train-test split
- Feature scaling
- Building a Logistic Regression or Neural Network model
- Model evaluation using metrics
- Confusion matrix analysis
- AUC-ROC curve evaluation (if simplified the task to two classes instead of five)

# Dataset

The dataset (heart_disease_uci) was taken from Kaggle:
https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data/data

## Results
- Because the number of samples is quite low, the classification with five classes is very poor.
- However, if we simplify the task to binary classification, then the predictive power of logistic regression is moderate to good, usually 80%.
- Neural network performs worse. Basically, it labels everyone as healthy.
