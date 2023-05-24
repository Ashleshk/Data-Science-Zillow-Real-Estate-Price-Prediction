# Zillow Real Estate Market Analysis

### Project Objectives
Every individual need to deal with the real estate or housing market at certain point of time in life. Having a good overview on the market will help in buying or selling the house in the market at right price.

In this project, Predict the price of unit area for houses given their features.


### Data Preprocessing
- **Drop Outliers** - there were outliers in `house price of unit area`, `longitude`, `distance to the nearest MRT station`.
- **Check Correlation** 
    - The `number of convenience stores` is **moderately correlated** to the `price of unit area`, while the `distance to the nearest MRT station` **negatively correlated**.
- **Preprocessing Data**
    - Convert transaction date to day, month and year columns
    - Scaling the data

## Modelling
- Polynomial Regression
- XGBRegressor
- Ridge Regression
- Lasso Regression

## Conclusion

1. **R2 Score of the models**

![R2 Score](https://github.com/Ashleshk/Data-Analysis-Zillow-Real-Estate-Market-Analysis/blob/main/Result/R2.png)

2. **RMSE of the models**
![RMSE results](https://github.com/Ashleshk/Data-Analysis-Zillow-Real-Estate-Market-Analysis/blob/main/Result/RMSE.png)

We can see that the XGBRegression Model performs the best
- R2 Score: 0.780957
- RMSE: 6.09142
