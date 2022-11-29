### TAXI ORDER ANALYSIS

Our task is to attract more drivers during the peak period, and for this we need to predict the number of taxi orders for the next hour. We have historical data on taxi orders at the airports. 
We need to build a model for such a prediction so that the RMSE on the test sample is not greater than 48.

We have noticed that the number of taxi orders is growing, increasing on weekends and decreasing during the week. We considered 2 models and changed the parameters to find the best prediction result. We chose RandomForestRegressor for prediction since RMSE is less than 48 (we got 44.948) and algorithm time was normal. We could consider other models to improve the prediction, such as Arima.

**KEYWORDS**: Python, Resampling, Augmented Dickey-Fuller Test, Linear Regression, RandomForestRegressor
