## Data Science Finance FTSE 100: Project Overview


* Extract and convert raw data into usable data (data engineer):
  - scrape the web and get the table that contains 100 companies listed on the London Stock Exchange with the highest market capitalisation in the index share Footsie 100.
  - removing unneeded columns and create a logarithmic daily return column for every ticker.
  - delete the unneded columns for each ticker and create a daily return column
  - combine all the tickers into one large dataframe.
  
* Organise and investigate the data using data visualization (data analysing):
  - Exploratory Data Analysis starting with simple methods such as generating descriptive statistics, find the correlation between tickers, check for the max value or min value throughout the perioud selected.
  - check the standard deviation of the return to find out the riskiest stock.
  - create interactive dashboard with panel for the ftse100 tickers adj close values and daily returns values.
  - create a heatmap for all the Tickers from ftse 100 daily return.
  - create a heatmap only for FTSE 100 index daily return.
  - check how many trades has been on every weekday for every ticker.
  - get the total for each ticker on every weekday of the Return, how many Trades, the Standard Deviation and the Coefficient of variation
  - find out which ticker has got the highest yearly ROI and which sector is coming from.

* Predict stock returns using various time series and machine learning models(Simple and Multiple Linear Regression, Logistic Regression, Facebook Prophet and Affinity Propagation Clustering) (machine learning)


### Code and Packages
**Python Version** 3.9.12

**Packages** pandas, numpy, bs4, matplotlib, cufflinks, hvplot, panel, prophet, requests, seaborn, session_info, sklearn, yfinance

**Libraries version** Please open the requirements.txt file
