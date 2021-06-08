# Time Series Analysis & Regression Analysis
### Using time series to predict Dollar to Yen exchange rate and regression analysis to predict future prices.
## Time Series Analysis
###  &emsp; 1. Loaded historical Dollar-Yen exchange rate futures data and applied time series analysis and 
###  &emsp; modeling to determine whether there is any predictable behavior.
###  &emsp; 2. Trimmed the dataset to begin on January 1st, 1990.
###  &emsp; 3. Used a Hodrick-Prescott Filter, decompose the Settle price into a trend and noise.
###  &emsp; 4. Forecasted Returns using an ARMA Model.
###  &emsp; 5. Forecasted the Settle Price using an ARIMA Model.
###  &emsp; 6. Yen Volatility Forecasted with GARCH

## Conclusion
### &emsp;1. Based on your time series analysis, would you buy the yen now?
###  &emsp; * I would buy Yen now based on the future 5 day forecast.
### &emsp;2. Is the risk of the yen expected to increase or decrease?
###  &emsp; * Risk is expected to increase.
### &emsp;3. Based on the model evaluation, would you feel confident in using these models for trading?
###  &emsp; * I would feel comfortable using these models with better understanding.

## Regression Analysis
### &emsp; 1. Data Preparation in which I created Returns and Lagged Returns to train and test data.
### &emsp; 2. Created a Linear Regression model and fit it to the training data.
### &emsp; 3. Make predictions using the Testing Data.
### &emsp; 4. Out-of-Sample Performance: Evaluate the model using "out-of-sample" data (X_test and y_test)
### &emsp; 5. In-Sample Performance: Evaluate the model using in-sample data (X_train and y_train)

## Conclusion
### Data performs better with Out of Sample data.
