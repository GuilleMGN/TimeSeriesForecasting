# TimeSeriesForecasting

## Description

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies.
In this assignment, we will test the many time series tools that we have learned in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.
We will do following tasks: 

1. Time series forecasting 
2. Linear regression modelling 

## Technologies
* pandas
* numpy
* datetime
* pathlib
* matplotlib
* statsmodel
* arch
* sklearn

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) </br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) </br>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) </br>

## Conclusions
### Return Forecasting: Time Series Analysis & Modelling with CAD-PHY Exchange rate data.
<b>Question:</b> Based on your time series analysis, would you buy the yen now? <br />
<b>Answer:</b> Based on the time series analysis, no, I would not buy the yen now. <br />
<br />
<b>Question:</b> Is the risk of the yen expected to increase or decrease? <br />
<b>Answer:</b> The risk of the yen is expected to increase. <br />
<br />
<b>Question:</b> Based on the model evaluation, would you feel confident in using these models for trading? <br />
<b>Answer:</b> The ARMA/ARIMA models are not as accurate and there are other things to consider before making this investment. I wouldn't feel confident in using these models for trading 

### Regression Analysis: Seasonal Effects with Sklearn Linear Regression
<b>Question:</b> Does this model perform better or worse on out-of-sample data as compared to in-sample data? <br />
<b>Answer:</b> We can see that the out-of-sample data (0.64) performs better than the in-sample-data (0.84) since it is lower. The model works best with data that it hasn't used before. 
