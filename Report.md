# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis:
>With machine learning we can now assess each lender history by creating models to predict the possible outcome.
  
* Explain what financial information the data was on, and what you needed to predict.
>Machine learning can classify loans as either low-risk (healthy) or high-risk (non-healthy) through predicting the data provided by the lending company. During the classification process, the logistic regression algorithm (lr) is used widely for machine learning model and can predict the best probability of results.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
>I was able to achieve an accuracy level of 97% by using the logistic regression model. The lower recall value for non-healthy loan is .94 which is compared to the healthy loan at .99 which outnumbers the non-healthy loan.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Accuracy is 97% with only the 1% of mistakes from healthy loan and 3% from non-healthy loan. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

>The logistic regression model really gives a clear view of accuracy when it comes to predicting results which is better than trainig on imbalance data and gives higher accuracy score. 

If you do not recommend any of the models, please justify your reasoning.
