# HydroWatch: Water Quality Monitoring and Prediction System

Welcome to the Water Quality Monitoring and Prediction System! This project aims to provide a user-friendly web application for monitoring and predicting water quality using machine learning models. Below is a detailed explanation of each component of the project, including a comprehensive analysis of the Jupyter Notebook used for model training and selection.


---
## Project Overview
The Water Quality Monitoring and Prediction System is designed to provide real-time monitoring and prediction of water quality based on various parameters. It leverages machine learning models to analyze and predict the safety of water, offering an easy-to-use interface for users.


### 355 ML.ipynb

In this Jupyter Notebook, various machine learning models are trained and evaluated to determine the best model for predicting water quality. The following models were tested:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- AdaBoost
- XGBoost
- Gaussian Naive Bayes
- Gradient Boosting

Here are the accuracy scores for each model:

| Model               | Accuracy Score |
|---------------------|----------------|
| Logistic Regression | 80.45%         |
| Decision Tree       | 95.48%         |
| Random Forest       | 97.14%         |
| KNN                 | 87.19%         |
| SVM                 | 76.75%         |
| AdaBoost            | 85.29%         |
| XGBoost             | 96.15%         |
| GaussianNB          | 80.38%         |
| GradientBoosting    | 90.68%         |

### Why Random Forest?

The Random Forest model was selected for building the web application due to its outstanding performance with an accuracy score of 97.14%. Random Forest is an ensemble learning method that operates by constructing multiple decision trees during training and outputs the mode of the classes for classification. Its high accuracy and robustness to overfitting make it an excellent choice for this project.
