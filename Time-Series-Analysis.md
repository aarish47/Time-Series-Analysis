# **Time-Series Analysis (With complete explanation!)**

## **Written by: Aarish Asif Khan**

## **Date: 12 January 2024**

> # **Introduction to Time Series Analysis**

- Time series analysis is a statistical technique used to analyze and extract patterns from time-ordered data. 

> # **Whats a Time series??**

- A time series is a sequence of data points recorded over successive intervals of time. These data points
are usually measured at regular intervals, but the interval can vary.

- It is widely used in various fields, including finance, economics, biology, and environmental science. 

> # **The main aim of Time series Analysis!**

- The primary goal of time series analysis is to identify patterns or trends within the data that
occur over time so as to make predictions about future observations based on past behavior.

- Another important aspect is to detect any anomalies/outliers which may indicate unusual events
or errors in the dataset.

> # **Types of Time Series Data**

There are mainly two types of time series datasets:

1. **Stationary Time Series** : If the mean value of the series does not change
over time and if the variance also remains constant then it's called Stationary Time Series.

2. **Non-stationary Time Series** : If the mean value of the series changes over time or if the variance changes with time then it's known as Non-stationary Time Series.

> # **Methods for Time Series Analysis**

- Another important aspect is to detect any anomalies/outliers which may indicate unusual events
or errors in the dataset.

Some common methods used in time series analysis including: 

1. **Descriptive Analysis:** Basic statistical measures such as mean, median, and standard deviation are used to summarize and describe the main features of the time series.

2. **Visualization:** Graphical methods, including line charts, scatter plots, and histograms, help in visually inspecting trends, seasonality, and anomalies in the data.

3. **Moving Averages:** Moving averages smooth out fluctuations in time series data by calculating the average of a set of consecutive data points. This can help identify trends.

4. **Exponential Smoothing:** Exponential smoothing methods assign exponentially decreasing weights to past observations. This is particularly useful for capturing trends and seasonality in a time series.

5. **Autoregressive Integrated Moving Average (ARIMA) Models:** ARIMA models combine autoregression (AR), differencing (I), and moving averages (MA). They are effective for handling non-stationary time series data.

6. **Spectral Analysis:** Examines the frequency domain properties of a time series using methods such as Fourier transforms. This is particularly useful for detecting periodic patterns.


> # **The weather Dataset**

- This dataset contains hourly temperature readings from a station in New York City from January 1
to July 31, 2015. 

- Each row represents one hour of temperature reading data with columns representing the date (in yyyy-mm-dd format) and the corresponding temperature (in Fahrenheit).

Example of the weather dataset:

![dataset](dataset.png)