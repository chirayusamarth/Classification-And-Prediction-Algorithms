# K-Nearest-Neighbours, Linear Regression And Logistic Regression

A standard machine learning pipeline usually consists of three parts. 1) Load and preprocess the
data. 2) Train a model on the training set and use the validation set to tune hyperparameters.
3) Test the final model and report the result. In this assignment, we will provide you a template
for each section (linear regression.py, knn.py, and logistic.py), which follows this 3-step
pipeline. TA's have provided step 1 - data loading and preprocessing code, and step 3 - output
format to report the results. You will be asked to implement step 2’s algorithms to complete the
pipeline. Do not make any modification to our implementations for step 1 and 3.
Please do not import packages that are not listed in the provided scripts. Follow the instructions
in each section strictly to code up your solutions. DO NOT CHANGE THE OUTPUT
FORMAT

Datasets

Regression Dataset The UCI Wine Quality dataset lists 11 chemical measurements of 4898
white wine samples as well as an overall quality per sample, as determined by wine connoisseurs.
See winequality-white.csv. We split the data into training, validation and test sets in the preprocessing
code. You will use linear regression to predict wine quality from the chemical measurement
features.

