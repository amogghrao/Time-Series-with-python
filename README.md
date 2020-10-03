# Time Series with Python
## Goals of this notebook Series
- Understand how to use Python to work with Time Series data
- Use pandas and Statsmodel to visualize Time Series data
- Be able to understand and implement wide variety of forecasting techniques on time series data, while understanding the pros and cons of each model used.

## 0. Before we get started
1. Install anaconda distribution with python. Just google 'anaconda download'. Install the 3.x version
2. Instead of individually explaining each libraries to be downloaded and explaining steps involved. Just download this [environment_file](https://drive.google.com/file/d/1abW_Gi9mwDAqHC4xmZqvpmeZ3Mq17PKr/view?usp=sharing) \(it's not a virus, I promise!) and run it in your anaconda command prompt.
    - Open anaconda command prompt, once you have the anaconda distribution installed, you should be able to find it on your search bar/terminal.
    - Copy the path where the `environment file` is saved.
    - Go to the folder where it is saved by typing `cd C:file path` -make sure you are in the folder where the the file is stored
    - Now we need to create the environment -  - type `conda env create -f environment_file.yml`
    
 This step has activated all the libraries and the respective versions of it
 
 
3. To activate this environment we need to use:
    - Type `conda activate time_series` in anaconda prompt
    
4. To deactivate this environment we need to use:
    - Type `conda deactivate` in anaconda prompt
    
 ## 1. [Numpy](https://github.com/amogghrao/Time-Series-with-python/blob/master/1.%20Numpy.ipynb)
 [Numpy](http://www.numpy.org/) is a library for scientific computing in Python. This is the first step in the journey of data science.
 
 ## 2.[Pandas](https://github.com/amogghrao/Time-Series-with-python/blob/master/2.%20Pandas.ipynb)
Python has long been great for data munging and preparation, but less so for data analysis and modeling. [Pandas](https://pandas.pydata.org/) helps fill this gap, enabling you to carry out your entire data analysis workflow in Python without having to switch to a more domain specific language like R. Methods and functions are pretty straight forword and intutive to use.

## 3. [Data Viz with Pandas](https://github.com/amogghrao/Time-Series-with-python/blob/master/3.%20Pandas%20visualization.ipynb)
Although python has various libraries which can be used for advanced data viz such as [matplotlib](https://matplotlib.org/) , [Seaborn](https://seaborn.pydata.org/), [Bokeh](https://bokeh.pydata.org/en/latest/) etc. However, most of these libraries offers a lot of customizable objects, which in turn increases the complexity and takes time to master.

Pandas has in- built Visualization capabilities, which is based on [matplotlib](https://matplotlib.org/) for easier usage. This comes at the cost of removing some customization options in the plot

## 4. [Handeling Time Series data with Pandas](https://github.com/amogghrao/Time-Series-with-python/blob/master/4.%20Time%20Series%20with%20Pandas.ipynb)
As the name suggests, most of our data will have a datetime component to it. We will going through how to handle datetime index in python.We will be going through:
      - DateTime Index and DateTime library
      - Time Resampling
      - Time Shifting
      - Rolling and Expanding
      - Time Series viz
      
## 5. [Introduction to Statsmodels with Smoothing Models](https://github.com/amogghrao/Time-Series-with-python/blob/master/5.%20Time%20Series%20with%20Statsmodels.ipynb)

[*`statsmodels`*](https://www.statsmodels.org/stable/index.html) is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration. An extensive list of result statistics are available for each estimator. The results are tested against existing statistical packages to ensure that they are correct. 

As its name implies, [*`statsmodels`*](https://www.statsmodels.org/stable/index.html) is a Python library built specifically for statistics. Statsmodels is built on top of [NumPy](https://numpy.org/), [SciPy](https://www.scipy.org/), and [matplotlib](https://matplotlib.org/), but it contains more advanced functions for statistical testing and modeling that you won't find in numerical libraries like NumPy or SciPy.

In this Notebook, we will cover:

- Introduction to Statsmodel
- ETS Decomposition
- Moving Averages
- Holt Winters Methods

**Note:** Please download a copy of `.ipnyb` notebook and run it in your local device.Some of the markdown cells are throwing error.

## 6. [Introduction to Forecasting models](https://github.com/amogghrao/Time-Series-with-python/blob/master/6.%20Introduction%20to%20Forecasting%20models.ipynb)

Last notebook, we focussed on fitting the model. So, the main purpose behind fitting a model is to predict what is next. What's our best guess for next month's value? For the next six months?

We will cover the following topics, which will start with forecasting the models we have learnt and set the stage for more complex models:

- Compare a Holt-Winters and exponential forecasted model to known data(test-train split)
- Understand stationarity, differencing and lagging (setting stage for ARIMA models)


## 7. [Introduction to ARIMA Models](https://github.com/amogghrao/Time-Series-with-python/blob/master/7.%20Introduction%20to%20ARIMA%20Models.ipynb)

ARIMA is an acronym that stands for **A**uto**R**egressive **I**ntegrated **M**oving **A**verage. It is a generalization of the simpler AutoRegressive Moving Average and adds the notion of integration.

- **AR**: Autoregression. A model that uses the dependent relationship between an observation and some number of lagged observations.<br>
- **I**: Integrated. The use of differencing of raw observations (i.e. subtracting an observation from an observation at the previous time step) in order to make the time series stationary.<br>
- **MA**: Moving Average. A model that uses the dependency between an observation and residual errors from a moving average model applied to lagged observations.
Each of these components are explicitly specified in the model as a parameter.<br>

A standard notation is used of ARIMA(p,d,q). The parameters of the ARIMA model are defined as follows:

- **p**: The number of lag observations included in the model, also called the lag order.<br>
- **d**: The number of times that the raw observations are differenced, also called the degree of differencing.<br>
- **q**: The size of the moving average window, also called the order of moving average.<br>

## 8. [Introduction to SARIMA(X) and VAR](https://github.com/amogghrao/Time-Series-with-python/blob/master/8.%20Introduction%20to%20SARIMA(X)%20and%20VAR.ipynb)
The SARIMA and VAR models are builds upon the ARIMA model. It includes the p, q, and d parameters, but also an extra set of parameters to account for time series seasonality. This parameter set– P, Q, D, and additional parameter m–is defined as follows:

- m : The seasonality of the model. For example, if the seasonality of time series is yearly, then m =12 
- P : The order of the seasonal autoregressive model.
- Q : The order of the seasonal moving average model.
- D : The number of seasonal differences applied to the time series.

<strong>NOTE:</strong> The statsmodels implementation of SARIMA is called SARIMAX. The “X” added to the name means that the function also supports <em>exogenous</em> regressor variables

        
        
 -------------------------------------------In-Progress----------------------------------------------------
    
