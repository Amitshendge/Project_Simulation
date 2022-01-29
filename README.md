# Project_Simulation
    Hadoop 3.3.1
    Python 3.8.10
    Jupyter notebook 6.4.6
    Pyspark 3.2.0
Problem Statement - Fetch the live stock data and use Linear Regression to predict the Stock Price

Here I have used alphavantage site to get stock price data in a csv file.
That csv file we have used in spark to create dataframe and did some transformations to get data cleaned sorted day wise.
Then used window function to use lead function to get next open price in same row so we can pass that column as label column in Linear Regression.
Finally used Linear Regression and compared predicted adn actual value on line chart.
