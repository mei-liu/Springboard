# Capstone Project 1: AAPL Stock Price Prediction

### Introduction
Under the market efficiency hypothesis, the market can be weak form, semi-strong form, or strong form efficient. If the stock market is at least weak form efficient, then technical analysis (trading based on past prices) cannot yield a consistent profit. The random walk theory is another prominent theory in finance that suggests future stock prices are independent of past stock prices, and thus technical analysis is unreliable. Moreover, many academic papers (Sullivan, Timmermann, and White (1999), etc.) conclude that simple trading rules using historical prices are not consistently profitable. However there is evidence that stock prices exhibit momentum (Jegadeesh and Titman, 1993) and seasonality (Heston and Sadka, 2008). 

### Objective
Are stock prices at least somewhat predictable? In this project, I apply machine learning techniques on historical AAPL stock prices to try and predict the next 10 days of stock prices. If stock prices exhibit price trends, the past prices can help predict future prices. If there is seasonality in the price trends, the timing (month of the year, day of the week) of the stock can further increase the predictability of stock prices. I also compare models that use only historical price based features with one that uses additional variables such as the earnings announcement data and Google trends. 

Going into the project, I expect that the final prediction results will be poor. After all, if stock prices were easily predictable, there wouldn’t be an entire field dedicated to studying stock market dynamics. The goal of the project is to see which model works best with the given data, and which features are the most important to the prediction. 

### Main Project Components
#### 1. Data Wrangling
- Features created using data/time, price, volume, bid-ask spread, earnings announcement surprise, and Google trend
#### 2. Exploratory Data Analysis
#### 3. Building and Testing Prediction Models
- Models used: simple moving average, autoARIMA, FBProphet, and XGBoost
