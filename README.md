# Advanced Regression Case Study
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know the following things about the prospective properties:

* Which variables are significant in predicting the price of a house
* How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* General Info
* Technologies Used
* Python Libraries Used
* Tools Used
* Conclusions
* Acknowledgements

## General Information
The company wants to know the following things about the prospective properties:

* Which variables are significant in predicting the price of a house
* How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.


Business Goal:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The below Steps performed as below:
    1. Data Understanding
    2. Data Cleaning
    3. Data Analysis (EDA) Univariate Analysis/ Bivariate Analysis/ Multivariate Analysis  
    4. Model Building
    5. Model Evaluation     

## Technologies Used
Python

## Python Libraries Used
numpy
pandas
matplotlib
seaborn
sklearn
statsmodels

## Tools Used
Jupiter Notebook
GitHub

## Conclusions
Ridge and Lasso Regression Model are built with optimum alpha calculated in GridSearchCV method.Optimum alpha = 20.0 for ridge and 0.001 for lasso model.Model evaluation is done with R2 score and Root Mean Square Error. Lasso Regression is chosen as final model for having slightly better R-square value on test data.


## Acknowledgements
    Developed By:
      Rajesh Sushir

## Contact
Created by https://github.com/RajeshSushir - feel free to contact me!

