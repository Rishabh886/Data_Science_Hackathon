# Data_Science_Hackathon
## Problem Statement
Artificial Intelligence is an integral part of all major e-commerce companies today. Today's online retail platforms are heavily powered by algorithms and applications that use AI. Machine learning is used in a variety of ways, from inventory control and quality assurance in the warehouse to product recommendations and sales demographics on the website.

Let’s say you want to create a promotional campaign for an e-commerce store and offer discounts to customers in the hopes that this might increase your sales.

You have been provided descriptions of products on Amazon and Flipkart, including details like product title, ratings, reviews, and actual prices. In this challenge, you will predict discounted prices of the listed products based on their ratings and actual prices.

## Dataset Description
This data contains total 16 columns (including id column), where price1 column (discounted price) is the target variable.

## Approach Used
1. I started with data visulization and identified important features impacting target variable
2. Did data cleaning and feature engineering to impute missing values and prepared the data for modelling
3. Used several regression algorithms such as Linear, Decision Tree, Random Forest, SVR, KNN, Adaboost, Gradient Boosting. Random Forest came out to be the best model
4. Performed hyperparameter tuning using GridSearchCV

## Result
Final RMSE score came out to be 202.69 for actual test data. My approach helped me to get in Top 41%.
