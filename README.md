# Rossmann-Sales-Prediction
Problem Statement: 

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

Solution Approach:

In our problem, there is two CSV file. So, at first, I merged them on the basis of “Store”. Then I deal with NAN values. After that, I did some Exploratory Data Analysis(EDA). In the EDA part first I looked for how “Sales” and “Customers’ varies with the Month, Year, on Days of the week, on each store, on state holiday, on school holiday, on different assortment, and on different store types. Then I want to know how “Promo” effect on Sales and customers on days of the week. Here I also show how many stores giving promos and how many stores are not giving promos. After that, I showed how the competition distance effect on sales. Then I want to see the relationship between each type of store and assortment. Penultimately I create a heat map to show the correlation among the features. 
Thereafter on machine learning creates a model for the forecast. Here first, I dropped out the highly co-related columns and create some dummy columns. Then I implemented 8 models: linear regression, lasso regression, ridge regression, elastic regression, decision tree regression, XGB regressor, random forest regressor, and bayesian linear regressor with the accuracy metrics r-squared, adjusted r-squared, root mean squared error and mean absolute percentage error.

Conclusion:

I preprocessed, feature-engineered the data, and examined different statistical / machine learning analysis for forecasting sales of each store. Then, I compared the methods’ predictive power by computing Mean Absolute Percentage Error (MAPE) and Adjusted R-Squared(Adj-R2). I found that the Decision Tree Regressor model performed the best with a MAPE score of 0.06 on the test data set with 97% variance will be predictable.

Interesting Insights:

Minimum sales and no. of customers were observed in the month of “January” where maximum sales and no. of customers were observed in the month of “December”. And in the weekdays' maximum sales and no. of customers were observed on “Monday” whereas minimum sales and no. of customers were observed on “Sunday”.
