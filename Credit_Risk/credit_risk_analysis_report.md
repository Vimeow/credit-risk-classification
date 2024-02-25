Date: 25/02/2024
Person: Vy Nguyen
Assignment: Module 20 - Credit risk classification using logistic regression model

# Module 20 Report

## Overview of the Analysis

- Purpose of the analysis:

In this Challenge, a dataset of historical lending activity from a peer-to-peer lending services was used to train and evaluate a Logistic Regression model based on loan risk. The trained model can be used to identify the creditworthiness of borrowers.

- Explain what financial information the data was on, and what you needed to predict:

The dataset contains information on loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt and loan_status. Using this dataset to train the Logistic Regression model so that it can predict the loan_status.

- Provide basic information about the variables you were trying to predict:

The variable that the model will predict is "loan_status" which encoded as "0" which means that the loan is healthy, and "1" which means that the loan has a high risk of defaulting.

- Describe the stages of the machine learning process you went through as part of this analysis:

The machine learning process included: (1) separate features (information) and the labels (loan_status); (2) split data in to training and testing sets; (3) create a Logistic Regression model; (4) fit the model to the training data set; (5) predict the labels using testing data set; and (6) evaluate model's performance using confusion matrix and classification report.

- Briefly touch on Logistic Regression model method:

Logistic regression is a statistical method used for binary classification tasks, where the goal is to predict the probability that an instance belongs to a particular class. Logistic regression models the probability using the sigmoid function. Sigmoid function calculates the probability (between 0 and 1) to predict if the data point is belong to group 0 or 1.

## Results

Describe the balanced accuracy scores and the precision and recall scores of the Logistic Regression model:

- In general, the Logistic Regression model made a prediction with a quite high accuracy (0.99).

- The Logistic Regression model predicts the `0` (healthy loan) correctly for almost the healthy loan cases (precision = 0.996 and recall = 0.996).

- However, for the `1` (high-risk loan) labels, there are some false negative and false positive in the prediction which resulting a lower precision (0.87) and recall (0.89) values as shown in the classification report for the model.

## Summary

- Summarise the results of the machine learning model, and include a recommendation on the model to use, if any:

The logistic regression model performed reasonably well on the provided dataset with high accuracy (0.99). However, in this example, it is more important to predict the potential "high-risk loan," and the precision and recall values of the model (0.87 and 0.89, respectively) are not very high when making predictions for this group, suggesting that another model should be investigated.
