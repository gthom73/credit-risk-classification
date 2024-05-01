**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** From our confusion matrix we can see that there were:
                - 578 instances where the model predicted the unfavorable loans correctly,
                - 18,660 instances where the model predicted the FAVORABLE loans correctly,
                - 105 instances where the model predicted unfavorable loans incorrectly. Loans were actually FAVORABLE but predicted as unfavorable, and
                - 41 instances where the model predicted FAVORABLE loan incorrectly. Loans were actually unfavorable but predicted as FAVORABLE.

Conclusion from the confusion matrix:
    I would conclude that this model would be conservative in nature and could be used as a guideline of deciding a yes/no decision on a loan. I like this model as a "feel good" test that a loan committee could use when deciding on loan amounts that were deemed material. For "small" loans where a customer is getting an approval over the internet, I would say 41 instances where the model predicted FAVORABLE when it should have been unfavorable would be an acceptable amount of risk to take.

Classification report conclusion:
    The model performed well in precision and f1 for favorable loans, 100% and 100%, but for unfavorable loans precision was at 85%. i believe this would be considered a reliable model based on the 85%. Any farther South of that figure and we would probably test further.







# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

**Answer:** From our confusion matrix we can see that there were:
                - 578 instances where the model predicted the unfavorable loans correctly,
                - 18,660 instances where the model predicted the FAVORABLE loans correctly,
                - 105 instances where the model predicted unfavorable loans incorrectly. Loans were actually FAVORABLE but predicted as unfavorable, and
                - 41 instances where the model predicted FAVORABLE loan incorrectly. Loans were actually unfavorable but predicted as FAVORABLE.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
