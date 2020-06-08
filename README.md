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


        
        
 -------------------------------------------In-Progress----------------------------------------------------
    
