![86621800_193076441962090_3832391733308555264_n](https://user-images.githubusercontent.com/57547960/92521082-a02a7600-f1ea-11ea-9c2b-9c7836a7d189.jpg)


# Credit-Card-Fraud-Detection-Analysis
Big Data Analysis on Credit Card Fraud Detection

Credit card fraud is one of the major problems in today’s world where all the transaction is based on online services. The project goal is to predict fraudulent credit card transaction base on features such as ‘Time’ and ‘Amount’ using different statistical models like Logistic Regression, GBT and KNN. We are also demonstrating the behavior of potentially fraudulent providers; the exploratory analysis will discover important variables to understand the fraudulent patterns in the provider's claims.

The dataset contains just numerical information factors which are the consequence of a PCA change. Shockingly, because of classification issues unique highlights are not given and more foundation data about the information is additionally not present.
The datasets contain transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

# Dataset description
Time - Number of seconds elapsed between the current transaction and the first transaction in the dataset
V1-V28 - PCA Dimensionality reduction to protect user identities and sensitive features(v1-v28)
Class - 1 for fraudulent transactions, 0 otherwise
Features V1, V2, ... V28 are the primary parts acquired with PCA, the main highlights which have not been changed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds slipped by between every exchange and the main exchange in the dataset. The component 'Amount' is the exchange Amount, this element can be utilized for instance dependent cost-delicate learning. Feature 'Class' is the response variable and it takes value 1 if there should arise an occurrence of fraud and 0 in any case.
Spark Techniques:
• Spark Session: This is a session created when we are running spark applications. It is a unified entry point for any spark application. It provides a way to interact with various spark functionalities.
• Pyspark: This helps to interface with resilient distributed datasets in apache spark and python. Py4J is a popular library integrated within pyspark that lets python interface dynamically with java virtual machine objects (RDD’s).
• Pyspark.sql.functions: This is one of the apache spark’s module that helps to work on structured data.
• Pyspark.ml.feature: This is a new package added to spark after version 1.2 that aims to provide a uniform set of high-level APIs which in turn helps users to tune or create their dataset by using practical machine learning pipelines.
