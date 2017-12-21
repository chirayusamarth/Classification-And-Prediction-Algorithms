# K-Nearest-Neighbours, Linear Regression And Logistic Regression

# Pipeline

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

# Datasets

**Regression Dataset:** The UCI Wine Quality dataset lists 11 chemical measurements of 4898
white wine samples as well as an overall quality per sample, as determined by wine connoisseurs.
See winequality-white.csv. We split the data into training, validation and test sets in the preprocessing
code. You will use linear regression to predict wine quality from the chemical measurement
features.

**Classification Datasets:** We describe three datasets that will be used for classification problems
in this homework. Each dataset corresponds to a JSON file named as $dataset$.json. JSON is
a lightweight data-interchange format, similar to a dictionary. After loading a dataset, you can
access its training, validation, and test splits using the keys ‘train’, ‘valid’, and ‘test’, respectively.
For example, suppose we load mnist subset.json to the variable x. Then, x\['train'\] refers to the
training set of mnist subset. This set is a list with two elements: x\['train'\]\[0]
containing the features of size N (samples) \times D (dimension of features), and x\['train'\]\[1\] containing the corresponding
labels of size N.
Next we will describe each one of the three datasets in more detail.

• toydata1 includes 240 data instances with binary labels that are linearly separable. The
data is split into a training set and a test set. You can look up training and test sets in
toydata1.json with \['train'\] and \['test'\], respectively.

• toydata2 includes 240 data instances with binary labels that are not linearly separable. The
data is split into a training set and a test set. You can look up training and test sets in
toydata2.json with \['train'\] and \['test'\] respectively.

• mnist subset: MNIST is one of the most well-known datasets in computer vision, consisting
of images of handwritten digits from 0 to 9
