# Anomaly Detection In Credit Card Fraud

This project involves analyzing a dataset of bank transactions using various machine learning models for classification and clustering. The dataset is sourced from Kaggle and includes PCA (Principal Component Analysis) transformed features.

## Overview

The primary objectives of this project are:
- To classify bank transactions into predefined categories using several machine learning classifiers.
- To cluster transactions based on their features to discover inherent patterns in the data.

## Dataset

- **Source**: Kaggle PCA Bank Transactions Dataset
- **Description**: The dataset contains PCA-transformed features of bank transactions. PCA is used to reduce the dimensionality of the dataset while retaining as much variance as possible.

## Feature Engineering

Feature engineering involves creating new features or modifying existing ones to improve model performance. For this project, feature engineering included the following steps:

1. **PCA Transformation**:
   - The original features were transformed using Principal Component Analysis (PCA) to reduce dimensionality while preserving variance. This helps in managing high-dimensional data and improving model performance.

2. **Feature Scaling**:
   - Features were scaled to ensure that they have a similar range, which helps improve the performance and convergence of some models.

3. **Feature Selection**:
   - Selection of relevant features was performed to reduce noise and improve the performance of the models. Techniques such as variance thresholding were used to remove less informative features.

## Models Used

### Classification Models

1. **Logistic Regression**:
   - A statistical model that applies a logistic function to model a binary dependent variable.
   
2. **Random Forest Classifier**:
   - An ensemble learning method that operates by constructing multiple decision trees and outputs the mode of the classes.

3. **Support Vector Machine (SVM)**:
   - A supervised learning model that finds the hyperplane that best separates different classes in the feature space.

4. **XGBoost Classifier**:
   - A powerful gradient boosting algorithm that combines the output of multiple weak models to improve predictive performance.

### Clustering Model

1. **K-Means Clustering**:
   - An unsupervised learning algorithm that partitions the dataset into K distinct clusters based on feature similarity.

## Results

The performance of the models on the PCA-transformed bank transactions dataset is as follows:

- **Logistic Regression**: Accuracy: 1.00
- **Random Forest Classifier**: Accuracy: 0.93
- **Support Vector Machine (SVM)**: Accuracy: 0.93
- **XGBoost Classifier**: Accuracy: 0.93
- **K-Means Clustering**: Accuracy: 0.55
