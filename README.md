# Loan-Approval-Prediction

## Project Description:

This project is about predicting likeliness of converting liability customers to personal loan customers using Logistic Regression, Random forest, KNN, Neural Networks, and Ensemble Models using “Bank Personal Loan Modelling”.
Dataset from Kaggle (https://www.kaggle.com/krantiswalke/bank-personal-loan-modelling) based on 5000 observations with 14 explanatory variables.

## Goal:

The project is aimed at implementing a model(s) to predict likeliness of converting liability customers to personal loan customers.
* Remove variables, build what is needed.
* Models: Logistic Regression, KNN techniques, RandomForest, Ensemble Learning & Neural Networks.
* Choose the best model having best accuracy.

## Business Problem:

This case is about a bank whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.

## Data Exploration and Preprocessing:

The Dataset contains data of 5000 customers with 14 explanatory variables. The data includes:
* Customer demographic information (age, income, etc.),
* The customer's relationship with the bank (mortgage, securities account, etc.)
* Customer response to the last personal loan campaign (Personal Loan).
* Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

## Data Cleaning:

* Removed rows which were having unknown values for features like Zip code and ID.
* Dropped rows with Nan/Null values.
* Dropped index column
* Checking for outliers, data entry errors
* Apply abs for "Experience"

## Models and their comparison:

We have implemented the below models:
* Logistic Regression
* RandomForest
* Classification using K-Nearest Neighbors
* Neural Networks
* Ensemble method

## Reasons for specific Model Selection:

### Logistic Regression:

Since we are dealing with a classification problem and expect some linear relationships between variables, we will use a logistic regression model to classify our data.

The Logistic Regression model on the testing data gives an accuracy value of 90.6%.

### Classification using K-Nearest Neighbors:

KNN stands for K-Nearest Neighbors. It is a supervised learning algorithm. It is often used as a benchmark for more complex classifiers such as Artificial Neural Networks (ANN) and Support Vector Machines (SVM). We have used 14 independent features for KNN implementation. A robust implementation must consider feature engineering, data cleaning, and cross-validation.
• K means clustering
• K = 3
• Sampling 80% of data for training the algorithms using random sampling

We have implemented KNN with different optimal weights by changing k values and this time the accuracy we achieved is 99.2%.


### Random Forest:





