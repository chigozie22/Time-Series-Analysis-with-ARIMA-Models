# Time-Series-Analysis-with-ARIMA-Models
A machine learning project that models and forecasts time series data accurately. This project achieved a minimum RMSE value and secured over 93% accuracy on test data

A time series is simply a series of data points ordered in time. In a time-series, time is often the independent variable, and the goal is usually to make a forecast for the future. Time series data can be helpful for many applications in day-to-day activities like:
  1. Tracking daily, hourly, or weekly weather data
  2. Monitoring changes in application performance
  3. Medical devices to visualize vitals in real-time

Auto-Regressive Integrated Moving Average (ARIMA) model is one of the more popular and widely used statistical methods for time-series forecasting. ARIMA is an acronym that stands for Auto-Regressive Integrated Moving Average. It is a class of statistical algorithms that captures the standard temporal dependencies unique to time-series data.The model is used to understand past data or predict future data in a series. It’s used 
when a metric is recorded in regular intervals, from fractions of a second to daily, weekly or monthly periods.ARIMAX (Auto-Regressive Integrated Moving Average Exogenous) is an extension of the ARIMA model, and similarly, SARIMAX (Seasonal Auto-Regressive Integrated Moving Average with Exogenous factors) is also an updated version of the ARIMA model. 

In this tutorial, SARIMAX model with Exogenous Factors scored highest with least RMSE value. It also predicted the test data to fine accuracy levels of about 93%

**Dataset**
There are two groups of datasets in this project and all can be found the data folder. 
The first dataset contains information on Rainfall Distribution in a certain region. Model built on this dataset can be found in RAINFALL.ipynb file in the models folder. 
Several models were trained to obtain the most proficient model that can predict rainfall. Since the most determining factor of rainfall is 'Humidity', we trained the model on the Humidity values contained in the dataset.
Proper modelling of this independent variable(humidity) can give great insigts in rainfall distribution and precipitation.

The second dataset contains information of Trading values for the precious metal GOLD. It is a time bound dataset including the Open, Close, High and Low of Gold within specified time period. Since the most important feature of stock analysis is the close, the models were trained to predict possible closing values for GOLD. Model related to this data can be found in the GOLD.ipynb file.

Several explanations are made in order to understand facts around time series data. Time series data analysis can be quite complex and require enough time to understand its properties.

Tui
