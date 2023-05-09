# MercadoLibre Search Traffic and Stock Price Analysis
## Project Overview
In this project, I will analyze the financial and user data of MercadoLibre, the most popular e-commerce site in Latin America, to help the company grow. I will explore the following questions:

* Can I predict the hourly Google Search traffic for MercadoLibre?
* How does the search traffic vary by seasonality and time of day?
* How does the search traffic relate to the stock price patterns of MercadoLibre?
* Can I create a time series model to forecast the future stock price of MercadoLibre?
## Data Sources
I will use two data sources for this project:

* The hourly Google Search Trends data for MercadoLibre from January 1st, 2016 to December 31st, 2020. This data shows how popular the search term “MercadoLibre” is on Google over time.
* The daily historical stock price data for MercadoLibre from Yahoo Finance from January 1st, 2016 to December 31st, 2020. This data shows the opening, closing, high, low, and adjusted closing prices, as well as the volume of trading for MercadoLibre.
## Data Analysis Steps
I will perform the following steps to analyze the data:

### Step 1: Find unusual patterns in hourly Google Search traffic.
I will use descriptive statistics and visualization techniques to identify any outliers, trends, or patterns in the hourly search traffic data. I will also investigate if there are any events or news that might explain the unusual patterns.

### Step 2: Mine the search traffic data for seasonality.
I will use time series decomposition to separate the search traffic data into three components: trend, seasonality, and noise. I will analyze how the search traffic varies by different time periods, such as daily, weekly, monthly, and yearly.

### Step 3: Relate the search traffic to stock price patterns.
I will use correlation analysis and scatter plots to examine the relationship between the search traffic and the stock price of MercadoLibre. I will also use linear regression to model the impact of search traffic on stock price.

### Step 4: Create a time series model by using Prophet.
I will use Prophet, a forecasting tool for time series data, to create a model that can predict the future stock price of MercadoLibre based on the historical data. I will evaluate the performance of the model by using metrics such as mean absolute error (MAE) and root mean squared error (RMSE).

## Project Summary
In this project, I will apply various data analysis techniques to explore the connection between the Google Search traffic and the stock price of MercadoLibre. The results of this project can help MercadoLibre understand its user behavior and market trends better, and optimize its business strategies accordingly.