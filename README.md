# Time Series with Python
## Goals of this notebook Series
- Understand how to use Python to work with Time Series data
- Use pandas and Statsmodel to visualize Time Series data
- Be able to understand and implement wide variety of forecasting techniques on time series data, while understanding the pros and cons of each model used.

## 0.Before we get started
1. Install anaconda distribution with python. Just google 'anaconda download'. Install the 3.x version
2. Instead of individually explaining each libraries to be downloaded and explaining steps involved. Just download this [environment_file](https://drive.google.com/file/d/1abW_Gi9mwDAqHC4xmZqvpmeZ3Mq17PKr/view?usp=sharing) \(it's not a virus, I promise!) and run it in your anaconda command prompt.
    - Open anaconda command prompt, once you have the anaconda distribution installed, you should be able to find it on your search bar/terminal.
    - Copy the path where the `environment file` is saved.
    - Go to the folder where it is saved with cd C:`file path` -make sure you are in the folder where the the file is stored
    - Now we need to create the environment -  - type `conda env create -f environment_file.yml`
    
 This step has activated all the libraries and the respective versions of it
 
 
3. To activate this environment we need to use:
    - Type `conda activate time_series` in anaconda prompt
    
4. To deactivate this environment we need to use:
    - Type `conda deactivate` in anaconda prompt
    
 ## 1. [Numpy](https://github.com/amogghrao/Time-Series-with-python/blob/master/1.%20Numpy.ipynb)
 [Numpy](http://www.numpy.org/) is a library for scientific computing in Python. This is the first step in the journey of data science.
    
