# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this data science analysis is to predict credit risk.  We're doing this by using the credit card dataset from LendingClub and deploying the following statiscal analysis:
- Random Over Sampler
- SMOTE algorithm
- Over and undersampling by using SMOTEENN

And by using the below machine learning models to reduce biases:
- Balanced Random Forest Classifer
- Easy Ensemble Classifier

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

# Balanced Ensemble
 ![This is an image](https://github.com/MSULioness/Credit_Risk_Analysis/blob/main/Resources/Balanced_Ensemble.jpg)
 
 The accuracy score is 79%
 
 # Easy Ensemble
 ![This is an image](https://github.com/MSULioness/Credit_Risk_Analysis/blob/main/Resources/Easy_Ensemble.jpg)
 
 The accuracy score is 93%
 
 # Naive Random
 ![This is an image](https://github.com/MSULioness/Credit_Risk_Analysis/blob/main/Resources/Naive_Random.jpg)
 The accuracy score is 65%
 
 # Smote OverSampling
 ![This is an image](https://github.com/MSULioness/Credit_Risk_Analysis/blob/main/Resources/Smote_Oversampling.jpg)
 
 The accuracy score is 62%
 
 # Under_OverSampling
 ![This is an image](https://github.com/MSULioness/Credit_Risk_Analysis/blob/main/Resources/Under_OverSampling.jpg)
 
 The accuracy score is 64%
 
 # UnderSampling
 ![This is an image](https://github.com/MSULioness/Credit_Risk_Analysis/blob/main/Resources/Undersampling.jpg)
 The accuracy score is 51%

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

I recommend using the Easy Ensemble Model due to the high balance accuracy %.
