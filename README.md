# Neural Network Charity Analysis
## Overview
The goal of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup by means of:
* Pre-processing Data for a Neural Network Model
* Compiling, Training, and Evaluating the Model
* Optimizing the Model

## Data Preprocessing

* Target Variable: IS_SUCCESSFUL
* Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
* Identification Variables (to be removed): EIN, NAME

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?

## Summary

Both the inital and optimized results of this model did not reach an accuracy of 75%, indicating that it is underperforming despite optimizations. A model such as a Random Forest Classifier might be better suited for classification.

### Initial Model Results

![image](https://user-images.githubusercontent.com/103383489/195188986-dea4f81e-0e10-40a3-ad1e-ce2ce6337370.png)

### Optimized Results

![image](https://user-images.githubusercontent.com/103383489/195188849-605baea4-5334-472e-b08f-6b6216d27833.png)


