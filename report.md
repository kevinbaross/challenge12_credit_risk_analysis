# Credit Risk Resampling Report

## Overview of the Analysis

When working with classifying loan, whether it is a risky loan or a less risky one, it is common to have an imbalanced dataset. This is because the number of healthy loan is significantly greater than the risky one. The purpose of this analysis is to use the machine learning model with the oversampling method to best predict the likelihood that a particular loan will be defaulted.

The dataset used in this model consists of the information on loan size, interest rate, borrower income, debt to income ratio, number of accounts borrowers have, derogatory marks, and total debts. These variables will be used to predicted whether the loan will be defaulted.

By using the `value_counts` function, we have seen that the default loan (denoted by 1) comprises of only 3% of the dataset. The rest of the data are non-defaulted loan (denoted by 0). This shows that there is an imbalanced in the data.

From this dataset, the first step is to divide it into training and testing data. The logistic regression is used to fit the model and predicts the ourcome. Because the dataset is imbalanced, resampling method has been used. Specifically, the `RandomOverSampler` is used to to resample the training data, so that the 0 and 1 becomes more balanced.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
