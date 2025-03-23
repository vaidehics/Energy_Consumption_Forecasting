This project focuses on forecasting energy consumption using time-series analysis and machine learning models. The dataset used is the Household Power Consumption dataset, which contains historical energy usage data collected at regular intervals. The objective is to predict future energy consumption trends to aid in efficient energy management and planning.

The data is preprocessed by handling missing values, converting timestamps, and resampling to an hourly frequency. Exploratory Data Analysis (EDA) is performed, including visualization of trends, seasonal decomposition, and correlation analysis to understand key patterns in energy usage.

Three different models are implemented to forecast energy consumption:

1. ARIMA (AutoRegressive Integrated Moving Average): A statistical approach that models the time series using past values and their differences.

2. Prophet: A model developed by Facebook that is robust to missing values and seasonality, making it suitable for forecasting energy consumption trends.

3. XGBoost: A powerful machine learning algorithm trained on past energy consumption data using time-series windowing techniques.

The models are trained on historical data and evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE). The results are visualized to compare the predictions with actual energy consumption values.
