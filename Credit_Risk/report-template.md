# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

	The purpose of this analysis was to train and test an linear regerssion model on a data set that contained information about peer-to-peer lending out comes. A possible use of this model is to predict future loads. 
* Explain what financial information the data was on, and what you needed to predict.
	
	The data provided included information about the load ( the ammount of the load and the interest rate), information about the borrewer ( income, Debt to income ratio, the number of accounts, if there is a derogatory mar, abd tghe total debt). The prediction is if the loan has a high risk of defaulting.
	
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
	
	The prediction was if the loan was at a high risk of defaulting. 0 or "False" ment low risk or a healthy load. 1 or "True" ment a high risk or an unhealthy load. 
* Describe the stages of the machine learning process you went through as part of this analysis.
	1. Load in the data.
	2. Seperate the inputs from the outputs.
	3. Split the data into a train set and test set.
	4. Create a linear regession model with the train data.
	5. Test the validitiy of the model with the test data. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

	This was done with a linear regerssion model but the maximum number of iterations was increases from the default to get the model to converge. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Linear Regression:
	   - accuracy score: .99
	   - precision: .92
	   - recall: .97

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
	(Only one model was test). More models have to be tested to see the best performer.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
	(Only one model was test).

If you do not recommend any of the models, please justify your reasoning.
My recomendation is to test other model to see if the precision of High Risk loans can be improved. 
