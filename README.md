# sparkify

## Project Overview
This is my capstone project on udacity called sparkify,here i'm using the small dataset but can use full dataset provide by udacity on there aws cloud.The purpose of the project is to predict churn for music company called sparkify like spotify.The small dataset is available on the kaggle.

## Problem Statement
There are lot of people who for unknow reasons churn out from some service. It is very difficult to get new customer and more difficult to retain the existing ones.By analyzing various patterns in the user log the attempt is to find those unknow reasons and give offer or incentive to such potential customers to retain them.

## Metrics
After the exploratotary data analysis we found out many features which can be help to train our machine learning model they are as following:

* Usage at different hours of the day.
* Usage at different days of a week.
* Different page types(Events).
* Time from downgrade to churn.

## Libraries 
* pandas
* numpy
* pyspark.sklearn
* pyspark
* datetime
* os

## Results
After cleaning of the data and transforming it by applying various operations over it the csv of dataset is created.The data is train on two important algorithms :

* Logistic Regression
* Random Forest

## Reflection
The overall project was interesting and challenging.I enjoyed the process of feature engineering as it gave me lot of pratice of the concepts which i learned from various courses.

## Improvement
The projec can be scaled to analysis full dataset on aws udacity to get better results. can use different supervised algorithm to improve the f1-score futher.

This is link to my medium blog https://medium.com/@jawale.mohit123/how-to-stop-them-before-they-leave-1bff47959b04
