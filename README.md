# Telco Customer Churn Prediction — Decision Tree

A supervised machine-learning classification project using the IBM Telco Customer Churn dataset.

## Project Highlights
- Data exploration and preparation
- Binary and One-Hot Encoding
- Decision Tree classification
- Overfitting detection
- Cost-Complexity Post-Pruning
- Confusion Matrix
- Precision, Recall, F1-score, and Accuracy

## Results
- Unpruned tree: ~99.88% train accuracy / ~72.00% test accuracy
- Pruned tree: ~79.08% train accuracy / ~77.83% test accuracy
- Churn recall: ~35%

The project shows how pruning reduced overfitting and improved generalization, while also demonstrating why accuracy alone is not enough for evaluating an imbalanced classification problem.

## Dataset
IBM Telco Customer Churn dataset from Kaggle (`blastchar/telco-customer-churn`).

## Tech Stack
Python, Pandas, NumPy, Matplotlib, scikit-learn, KaggleHub, Jupyter Notebook.
