# Titanic Challenge

This repository contains my solutions to the Titanic Challenge on Kaggle. I have approached the problem using two different machine learning algorithms: Random Forest and Logistic Regression.

## Problem Description

The Titanic Challenge is a popular machine learning competition on Kaggle. The goal is to predict whether a passenger on the Titanic survived or not, based on various features such as age, gender, ticket class, and cabin.

## Dataset

The dataset provided for this challenge consists of two files: `train.csv` and `test.csv`. The `train.csv` file contains the training data with the known labels, while the `test.csv` file contains the test data without labels. The task is to build a model using the training data and make predictions on the test data.

## Random Forest Approach

In my first approach, I used the Random Forest algorithm to tackle the Titanic Challenge. Random Forest is an ensemble learning method that combines multiple decision trees to make predictions. It is well-suited for this problem because it can handle both categorical and numerical features effectively.

To preprocess the data, I performed feature engineering by extracting relevant information from the existing features, such as creating a new feature to represent the family size of each passenger. I then encoded categorical features using one-hot encoding and handled missing values appropriately.

After preprocessing, I trained a Random Forest classifier on the training data and tuned the hyperparameters using cross-validation. Finally, I made predictions on the test data and submitted the results to Kaggle.

## Logistic Regression Approach

In my second approach, I employed Logistic Regression to solve the Titanic Challenge. Logistic Regression is a popular algorithm for binary classification problems, making it suitable for predicting survival outcomes in this case.

Similar to the Random Forest approach, I performed data preprocessing by handling missing values and encoding categorical features. Additionally, I scaled the numerical features to ensure all variables were on a similar scale.

After preprocessing, I trained a Logistic Regression model on the training data and tuned the regularization parameter using cross-validation. I then made predictions on the test data and submitted the results to Kaggle.

## Evaluation and Results

Both approaches were evaluated using the accuracy metric, which measures the percentage of correct predictions. The performance of each approach on the test data is as follows:

- Random Forest: achieved an accuracy of approximately 80,44%
- Logistic Regression: achieved an accuracy of approximately 81%

The results from both models demonstrate the effectiveness of these algorithms in predicting survival outcomes in the Titanic Challenge.

## Conclusion

In conclusion, I successfully solved the Titanic Challenge on Kaggle using two different approaches: Random Forest and Logistic Regression. These models showcased the potential of machine learning algorithms in predicting survival outcomes based on various passenger features. I hope my work here can serve as a reference for others interested in exploring this challenge.