# Dont-Overfit-Self-Case-Study-1

## Overview

One of the main objectives of predictive modeling is to build a model that will give accurate predictions on unseen data which will only be possible when we make sure that they have not overfitted the training data. Before going to understand how to ensure that our model hasn’t overfitted training data, let’s first get aware of the reasons which lead the model to get overfitted.
	
There are many reasons for the same, yet we would like to point out some major reasons. First, being of fewer data points in training samples, second is the dataset being imbalanced, and last but not the least, the complex nature of the model.
	 
In this case study, we are going to handle the same problem of overfitting and the challenging part is to make a model with 250 data points in the train set and predict the binary target accurately for 19750 unseen data points in the test set. The dataset has 300 features of a continuous variable.
	
* The dataset is obtained from the link: https://www.kaggle.com/c/dont-overfit-ii/data
	
## Files
* train.csv - the training set. 250 rows.
* test.csv - the test set. 19,750 rows.
* sample_submission.csv - a sample submission file in the correct format
## Columns
* id- sample id
* target- a binary target of mysterious origin.
* 0-299- continuous variables.
##  Evaluation Metric 
* AUROC
