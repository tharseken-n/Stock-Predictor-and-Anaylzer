# Stock Predictor and Analyzer

This is an extremely basic stock predictor and analyzer Python script. It scrapes the web (Wikipedia S&P500 list and Yahoo Finance) for stock ticker information and analyzes the data to predict future stock prices.

## Motivation
Over the past few months, I recently became interested in investing money in stocks and the stock market. The stock market is one possible way to invest hard-earned money. Though there are other ways to invest money, the stock market often provides the highest potential return. Though it seemed like an easy way to make money, I quickly learned that the market was often times volatile, and hard to predict for an investing beginner. That is when I decided to use my programming knowledge, a few online resources, and my desire to learn and apply basic machine learning principles to create a tool. The goal of the tool was to help predict stock prices and easily categorize them in to buy, sell, and hold categories.

## Languages, Frameworks, and Libraries Used
```
Languages: 
  - Python

Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Sci-Kit Learn
  - BeautfulSoup
```

## Getting Started
To run this project, simply clone this repo.

First, run the file "sp500.py". This will scrape Wikipedia's website for the latest S&P500 company stock list. It will then use Yahoo finance to obtain the stock prices for each company on the Wikipedia list. This will also combine the closing prices for each company in to one pandas dataframe. This will allow for easy data manipulation and visualization.

Next, run the file "preprocessData.py". This will prime the combined stock data for machine learning classification. The classification process is done using the Python libary SciKit Learn. There are a few different classifier methods used, and the best one is selected using a voting classifier.

##### Inspiration and Resources
> Web Scraping with Python: Collecting Data from the Modern Web by Ryan Mitchell

> Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython by Wes McKinney

> Sentdex Python Programming For Finance
