# Forecasting-Vehicle-Sales

## Time series forecasting of lightweight vehicle sales

The project involved utilizing advanced techniques such as ARMA, SARIMA, and LSTM to analyze and forecast sales data. The insights gained from this project can be particularly useful in identifying and responding to changes in consumer behavior, economic trends, and market demand.

## Key Features

- ARMA Model: An AutoRegressive Moving Average (ARMA) model is implemented to capture the linear dependencies and trend in the sales data.
- SARIMA Model: A Seasonal AutoRegressive Integrated Moving Average (SARIMA) model is utilized to capture both the trend and seasonal patterns in the sales data.
- LSTM Model: A Long Short-Term Memory (LSTM) neural network model is implemented to capture complex temporal dependencies and non-linear patterns in the sales data.
- Model Evaluation: The project includes comprehensive evaluation metrics to assess the performance of each model, such as Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE), and RMSE (MinMax Scaled) for comparison.
- Model Comparison: The project provides a comparative analysis of the ARMA and SARIMA models to identify their strengths and limitations for forecasting lightweight vehicle sales.

## Requirements

- Python 3.0 or higher
- NumPy
- Pandas
- Statsmodels
- TensorFlow
- Keras

## Results

For the ARMA model, the evaluation metrics on the test set are as follows:

Metric               │      Value
──────────────────────┼────────────
MAPE                 │  10.7686
RMSE                 │ 188.373
RMSE (MinMax Scaled) │   0.132328

For the SARIMA model, the evaluation metrics on the test set are as follows:

Metric               │      Value
──────────────────────┼────────────
MAPE                 │  10.5814
RMSE                 │ 219.644
RMSE (MinMax Scaled) │   0.275274

These metrics demonstrate the performance of each model in terms of accuracy and forecasting capability. The RMSE (MinMax Scaled) provides a comparison of the models' performance after scaling the data.
