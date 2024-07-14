# Car Price Prediction

# About Dataset
The dataset [car_price.csv](https://github.com/mhaffizhhh/Car_Price_Prediction/blob/main/car_price.csv) is a collection of data on car prices, containing details about the cars being sold. 
I will create a regression model to predict the price of a car based on its condition. 
Then, I will evaluate the models to determine which algorithm performs best in predicting the prices.



Here I will make predictions on the car_price.csv dataset using a regression model. Why use regression?
Because the dependent variable is of a numerical type, regression can be used to make predictions. There are several types of regression models
what I use here is:
1. Multiple Linear Regression
2. Polynomial Regression
3. Decision Tree Regression
4. Random Forest Regression
5. Support Vector Regression

We will see which model provides the best model among the other models.

In the ML_Regression.ipynb file, it is found that predictions using the Random Forest Regression model produce an r square value
the highest among the other models, meaning that the Random Forest Regression algorithm is very good for predicting the car_price.csv dataset.
