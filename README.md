# ENCRYPTIX
This project mainly focuses on handling imbalanced datasets and detecting credit-card frauds using Following Machine Learning Algorithms:

a) Logistic Regression

b) RandomForestClassifier

c) DecisionTreeClassifier

These models are fittted to different datasets acquired after undersampling.

ABOUT DATASETS:

URL : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This datasets have 52 frauds out of 11959 transactions. It is highly unbalanced, the positive class--1.0 (frauds) account for 0.00434% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features are not provided and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

Feature Time contains the seconds elapsed between each transaction and the first transaction in the dataset.But, we did not consider Time for training purpose as it is of no use to build the models and may not impact our target variable.

The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.

Feature Class is the response variable and it takes value 1.0 in case of fraud and 0.0 otherwise.

STEPS :
Importing Libraries & Loading Datasets.

Data Preprocessing & Preparing Datasets.

Exploratoty Data Analysis(EDA) & Visualization.

Handling Imbalanced Datasets.

Conclusions.

Conclusions:
a) Out of all 3 Machine Learning Models used, Random Forest Classifier works efficiently with Maximum Accuracy of 95.238% acheived with Undersampling technique.

b) Undersampling Techniques proved to be efficient for handling Imbalanced Datasets.

c) RandomForest, DecisionTree, logistic regression work efficiently even for this Imbalanced Datasets.
