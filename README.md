Predicting Customer Retention in the E-Commerce Industry in Indonesia: A Machine Learning Approach
===================================

This is a repository for customer retention prediction project for completing MSc Business Analytics at UCL. Created by [Louis Bernardus](https://github.com/louisbernardus).

## How to Use this Repo
The project is divided into three notebooks:
* First Notebook - Data Cleaning & EDA.ipynb
* Second Notebook - Feature Engineering
* Third Notebook - Run Model and Eval

## Abstract
For the past decade, managing complex customer retention has presented a constant challenge for the retail industry. As a result, companies invest in customer relationship management (CRM) tools and leverage their data to understand customers' behaviour, identify profitable segments, predict the non-recurring (churning) customers, and formulate their retention strategy.
Previous studies mainly highlighted this problem in an arguably more traditional industry, such as telecommunications or airlines. Moreover, the focus often falls on finding the best model by implementing and comparing state-of-the-art algorithms without emphasising how it applies in modern business settings.
This research used e-commerce data from Indonesia in 2021, one of the fastest-growing countries for online retail, to predict whether a customer will make another transaction in the following 30 days. Several algorithms are compared to ensure a robust analysis: decision tree, random forest, XGBoost, neural network, and voting classifier. Overall, the random forest has the best accuracy (0.751243). In contrast, XGBoost has the best precision (0.816262), and the neural network has the best recall (0.715383).
Finally, two business application approaches, applying both precision and recall metrics, are examined in detail to encourage implementation.