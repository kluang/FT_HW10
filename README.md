# Time Series and Regression Analysis
![yen](yen.jpg)

## Time Series Forecasting
By uploading historical data of yen from 1976 to 2019, we are trying to see if any predictions of behavior could be forecasted by using time series analysis and modeling.

Based on the time series analysis I would not by the yen now, the risk of yen seems high and returns do not look good for short term. 


## Linear Regression Forecasting
Using the same yen data as above we built a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects.

This model performs better on the Out-of-Sample data, the data that the model has not seen before, contrary to the In-Sample data the model was trained on.

Lower values of RMSE indicate better fit. RMSE is a good measure of how accurately the model predicts the response, and it is the most important criterion for fit if the main purpose of the model is prediction.
