# Chapter 2. end to end project
## Configure environment
install:
- jupyter
- numpy
- matplotlib
- pandas
- scipy
- scikit-learn

Create jupyter notebook
Download housing price data from https://raw.githubusercontent.com/ageron/handson-ml/master/datasets/housing/housing.tgz
Look at the data using pandas  
pd.head() displays sample of data rows  
pd.info() displays column info  
pd.describe() displays statistical info about data  
pd['row'].value_counts() useful to view categorical data  
plot data with scatter (x lang, y lat)  
plot data with scatter  
prepare data (via transformation function). using functions have multiple advatages  
- can work on new data (fresh data set)
- can be used to preprocess data at production
- build a library of transformation function to use with other projects
- easier to try different combinations of transformations