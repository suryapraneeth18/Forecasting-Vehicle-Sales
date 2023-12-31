# Forecasting-Vehicle-Sales
## Time series forecasting of light weight vehicle sales
The project involved utilizing advanced techniques such as ARMA, SARIMA and LSTM to analyze and forecast sales data. The insights gained from this project can be particularly useful in identifying and responding to changes in consumer behavior, economic trends, and market demand.
## Key Features
- ARMA Model: An AutoRegressive Moving Average (ARMA) model is implemented to capture the linear dependencies and trend in the sales data.
- SARIMA Model: A Seasonal AutoRegressive Integrated Moving Average (SARIMA) model is utilized to capture both the trend and seasonal patterns in the sales data.
- LSTM Model: A Long Short-Term Memory (LSTM) neural network model is implemented to capture complex temporal dependencies and non-linear patterns in the sales data.
## Requirements
Python 3.0 or higher
- NumPy
- Pandas
- Statsmodels
- TensorFlow 
- Keras
## Results
<p>For the ARMA model, the evaluation metrics on the test set are as follows:</p>

MAPE: 10.7686\
RMSE: 188.373\
RMSE (MinMax Scaled): 0.132328
<p>For the SARIMA model, the evaluation metrics on the test set are as follows:</p>

MAPE: 10.5814\
RMSE: 219.644\
RMSE (MinMax Scaled): 0.275274
<p>For the LSTM model, the evaluation metrics on the test set are as follows:</p>

Train Score: 4.11 RMSE\
Test Score: 4.49 RMSE\
LSTM forecast
![download](https://github.com/suryapraneeth18/Forecasting-Vehicle-Sales/assets/75241973/9444e856-df04-4e75-a428-79523fc10b4c)
<p>These metrics demonstrate the performance of each model in terms of accuracy and forecasting capability. The RMSE (MinMax Scaled) provides a comparison of the models' performance after scaling the data.</p>
