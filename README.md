Overview

This project implements multiple machine learning models to predict housing prices based on available features. Since the Boston housing dataset is deprecated, we use the California Housing Dataset instead.

Dataset

Source: sklearn.datasets.fetch_california_housing()

Features:

8 numerical features representing housing attributes (e.g., median income, total rooms, etc.).

Target:

Median house value (in $100,000s).


Models Used

Linear Regression

Decision Tree Regressor

K-Nearest Neighbors (KNN) Regressor

Bagging Regressor (with Grid Search for Hyperparameter Tuning)




Implementation Steps

Load and explore the dataset.

Split the data into training (80%) and testing (20%).

Train multiple regression models and evaluate performance using R² score.

Implement Bagging Regressor to improve predictions.

Use GridSearchCV to optimize hyperparameters.


Results

The models are evaluated using the R² score (higher is better).

Model

R² Score (Test Set)

Linear Regression - 0.61

Decision Tree - 0.74

KNN (k=5) - 0.67

Bagging Regressor - 0.78


Dependencies

Python 3.8+,scikit-learn,numpy,pandas
