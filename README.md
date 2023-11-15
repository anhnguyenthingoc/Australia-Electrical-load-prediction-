# Australia-Electrical-load-prediction-
Australian load dataset. 

This data is taken every 01:01 every day, from May 21, 2019 to June 30, 2020.

There are a total of 395 entries in the Australian database. 

Link: https://content.iospress.com/articles/journal-of-intelligent-and-fuzzy-systems/ifs189884

Citation: 

Dat, Nguyen Quang et al. ‘Hybrid Online Model Based Multi Seasonal Decompose for Short-term Electricity Load Forecasting Using ARIMA and Online RNN’. 1 Jan. 2021 : 5639 – 5652.

Abstract: Short-term electricity load forecasting (STLF) plays a key role in operating the power system of a nation. A challenging problem in STLF is to deal with real-time data. This paper aims to address the problem using a hybrid online model. Online learning methods are becoming essential in STLF because load data often show complex seasonality (daily, weekly, annual) and changing patterns. Online models such as Online AutoRegressive Integrated Moving Average (Online ARIMA) and Online Recurrent neural network (Online RNN) can modify their parameters on the fly to adapt to the changes of real-time data. However, Online RNN alone cannot handle seasonality directly and ARIMA can only handle a single seasonal pattern (Seasonal ARIMA). In this study, we propose a hybrid online model that combines Online ARIMA, Online RNN, and Multi-seasonal decomposition to forecast real-time time series with multiple seasonal patterns. First, we decompose the original time series into three components: trend, seasonality, and residual. The seasonal patterns are modeled using Fourier series. This approach is flexible, allowing us to incorporate multiple periods. For trend and residual components, we employ Online ARIMA and Online RNN respectively to obtain the predictions. We use hourly load data of Vietnam and daily load data of Australia as case studies to verify our proposed model. The experimental results show that our model has better performance than single online models. The proposed model is robust and can be applied in many other fields with real-time time series.
