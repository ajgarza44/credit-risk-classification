# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the healthy vs high-risk potential of borrowers of loans.
* Explain what financial information the data was on, and what you needed to predict.
Past lending transactions from a peer-to-peer lending platform were used to predict credit worthiness of borrowers.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
A Logistic Regression Model was used to determine accuracy, precision, and recall scores from the data

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    * The number of healthy loans is greather than the number of unhealthy laons.
    * The model has an accuracy of 99%, the precision score for healthy loans is 100% vs the unhealthy at 85%.
    * The recall scoare is 99% for prediciton of healthy loans and 91% for high-risk loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
Only one type of Modle was created with the data provided. I do not recommend this model solely because there is no other model created therefore there is no comparison to determine which would be best, imbalanced or balanced data. 