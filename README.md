                                          ![](https://miro.medium.com/max/482/0*tVCene42rgUTNv9Q.png)

### Introduction
___

COVID-19 Prediciton for Pakistan using the Facebook Prophet time series forecasting model.

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

Prophet is open source software released by Facebook's Core Data Science team. It is available for download on CRAN and PyPI.

### Data Source
___

Data downloaded from 2019 [Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

[Time Series Data](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series) data used for **confirmed** cases only.

### Installation in Python
___

Prophet is on PyPI, so you can use pip to install it:

#bash

$ pip install fbprophet

### Compatibility
___

Google Colab

Python 3.0

Version 0.6 (2020.03.03)
