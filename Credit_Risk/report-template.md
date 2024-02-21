# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

- Explain the purpose of the analysis.

"In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers."

- Explain what financial information the data was on, and what you needed to predict.

information = loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt,

predict = loan_status

- Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

"A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting."

- Describe the stages of the machine learning process you went through as part of this analysis.

Separate features (information) and the labels (loan_status).

Split data in to training and testing sets.

Create a model

Fit the model to the training data set.

Predicted the labels usinf testing data set.

Evaluate model's performance.

- Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

Calculating the probability using sigmoid function (between 0 and 1), then predict if the data point is belong to group 0 or 1.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

- Machine Learning Model 1:

  - Description of Model 1 Accuracy, Precision, and Recall scores.

- Machine Learning Model 2:
  - Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

- Which one seems to perform best? How do you know it performs best?
- Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
