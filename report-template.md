# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

- Explain the purpose of the analysis.
  The purpose of this analysis is to train and evaluate a model that can be used to identify the creditworthiness of borrowers.
- Explain what financial information the data was on, and what you needed to predict.

The data was historical lending activity from peer-to-peer lending services companies and if it was healthy or not.

- Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  The variable y had 0 as a healthy loan and 1 as a at-rick loan.
- Describe the stages of the machine learning process you went through as part of this analysis.
  I set the random state, trained the model, tested adn predicted.
- Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
  I used Logistic Regression and generated a confusion matrix.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

- Machine Learning Model 1:

  - Description of Model 1 Accuracy, Precision, and Recall scores.
    precision recall f1-score support

               0       1.00      0.99      1.00     18765
               1       0.85      0.91      0.88       619

        accuracy                           0.99     19384

    macro avg 0.92 0.95 0.94 19384
    weighted avg 0.99 0.99 0.99 19384

- Machine Learning Model 2:

  - Description of Model 2 Accuracy, Precision, and Recall scores.
    precision recall f1-score support

               0       1.00      0.99      1.00     18765
               1       0.84      0.99      0.91       619

        accuracy                           0.99     19384

    macro avg 0.92 0.99 0.95 19384
    weighted avg 0.99 0.99 0.99 19384

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

- Which one seems to perform best? How do you know it performs best?
  The second model preformed better than the first since the recall is higher on the second.
- Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  It is more important to predict the 0.
  If you do not recommend any of the models, please justify your reasoning.
