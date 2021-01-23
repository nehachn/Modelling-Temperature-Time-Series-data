# Modelling and Forecasting of Temperature (monthly) Time Series Data

Time series modelling and forecasting – a method that predicts future values by analysing past values plays an important role in many practical fields.The
forecasting of temperature on a seasonal time scale has been attempted by many researchers by different techniques at different times across the globe. It is a
challenging task to forecast temperature on a monthly and seasonal time scale.

This project presents a Seasonal Autoregressive Integrated Moving Average (SARIMA) model to long term temperature data of India for the period of 117 years (1901-2017).

# Dataset
The data is obtained from the National Government Data Website: [data.gov.in](https://data.gov.in/catalog/all-india-seasonal-and-annual-mean-temperature-series?filters%5Bfield_catalog_reference%5D=349261&format=json&offset=0&limit=6&sort%5Bcreated%5D=desc)

The dataset contains - Temperature of each month over 117 years (1901 - 2017) of India in Celsius.
Each row specifies a year( 1901 - 2017), and each column specifies temperature for a particular month.
There were no missing values in the dataset.

The csv file can be found [here](https://drive.google.com/drive/folders/12zqc19nDupRdVkEuQRAH9vfuLWyBDmAy)

# Methodology
This project uses the Box Jenkins Method for data analysis and forecasting.
The Box-Jenkins method refers to the iterative application of the following three steps:

Identification: Using plots of the data, autocorrelations, partial autocorrelations, and other information, a class of simple ARIMA models is selected. This amounts to estimating appropriate values for p, d, and q.

Estimation: The phis (ɸ) and thetas (Θ) of the selected model are estimated using least square estimation, maximum likelihood techniques etc.

Diagnostic Checking: The fitted model is checked for inadequacies by considering the autocorrelations of the residual series (the series of residual or error values).

# Libraries
Numpy

Pandas

Mathplotlib

Scikit-learn

Statsmodels - provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration





