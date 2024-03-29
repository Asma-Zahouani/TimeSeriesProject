# Time Series Analysis

Project
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Asma-Zahouani/TimeSeriesProject/master?labpath=index.ipynb
)

- In mathematics, a time series is a series of data points indexed in time order. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data.

- Time series analysis is a specific way of analyzing a sequence of data points collected over an interval of time. In time series analysis, analysts record data points at consistent intervals over a set period of time rather than just recording the data points intermittently or randomly.

## :clipboard: This is a mini project with the following tasks:
* Importing necessary packages
* Extracting valuable information from the dataset
  * Checking The Shape of The Dataframe
  * Checking The Null Values
  * Checking Duplicated Values
  * Checking The Types Of Data
* Analysis and transforms
  * Time series decomposition
    * Level
    * Trend
    * Seasonality
    * Noise
  * Stationarity
    * AC and PAC plots
    * Rolling mean and std
    * Dickey-Fuller test (ADF)
  * Making our time series stationary
    * Difference transform
    * Log scale
    * Smoothing
    * Moving average
* Forcasting with MLP

  

## :file_folder: dataset
For the purpose of implementing time series forecasting technique , i will utilize gold pricing from  [Data source](https://data.nasdaq.com/) ,The following snippet shows a quick one-liner to get your hands on gold pricing
information since :date: 1970s :

|    | Date                |   Value |
|---:|:--------------------|--------:|
|  0 | 1970-01-01 00:00:00 |    35.2 |
|  1 | 1970-04-01 00:00:00 |    35.1 |
|  2 | 1970-07-01 00:00:00 |    35.4 |
|  3 | 1970-10-01 00:00:00 |    36.2 |
|  4 | 1971-01-01 00:00:00 |    37.4 |




## Includes
* Data understanding
* Data preprocessing
* Analysis
  * Transforms
  * Forcasting with MLP
* Conclusion






<img src="images/MLP.png"
     alt="Markdown Monster icon"
     style=" width:fit-content !important;margin-left:32% !important;" />


