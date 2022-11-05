# Housing Price Regression
> This is a regression use-case to build a robust and generalizable model to predict housing prices in Australian market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

This repo build regression models using Ridge and LASSO and grid search cross-validation techniques to find the generalizable model to predict the house prices. It then identifies the important variables based on absolute coefficient values.

## Conclusions
- Top 5 important variables are similar between LASSO and Ridge.
- There are some correlated variables within top 5 for Ridge but not for LASSO.

## Technologies Used
- Python - version 3.9.1
- pandas - version 1.2.3
- scikit-learn - version 0.24.2


## Contact
Created by [@nagakartheek-ms] - feel free to contact me!
