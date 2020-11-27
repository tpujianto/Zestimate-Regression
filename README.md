# Zestimate Regression

The objective of this project is to predict the logerror between the predicted log error and the actual log error. The log error is defined as:
logerror=log(Zestimate)−log(SalePrice)
In other words, the goal of the project is to predict the difference between the Zestimate and the actual sales price of homes.

## Data

[Kaggle](https://www.kaggle.com/c/zillow-prize-1) provided real estate data from three counties in Southern California: Los Angeles, Ventura County, and Orange County. There are (2) sets of data given: training set with the actual logerror and house features data. The house features data consisting of 2,985,217 observations (rows), each with 56 features. The training set, however, has 90,275 observations (rows).

## Project Outline
1. Exploratory Data Analysis (EDA)
2. Feature Engineering
3. Modeling

## Results 
LightGBM was the best performing model with MAE .0527.

