# Momentum-Trading-Strategy-using-Moving-Average

#### The goal for this project is to create a Momentum Trading Strategy using Moving Averages which can beat the market. 
#### Beating the Market: The goal of many trading strategies is to achieve higher returns than the market average over the same period. In this context, "beating/outperforming the market" means generating a higher return with our strategy than what we would have earned with a simple buy and hold approach.
#### To get started we will pull price data from Yahoo Finance using Pandas DataReader. I am going to choose Tesla (TSLA) as my stock.
### Choosing the Strategy's Time Frame:
#### The first step when setting up a momentum trading strategy is deciding on the time frame. I pulled the price data for the last 150 days of trading for Tesla. In order to get the last 150 days consistently I am going to use date.today()and timedelta. Using timedelta, the start date will be 150 days in the past from the current date. This will collect data for approximately the previous 103 trading days when accounting for weekends and holidays. NOTE: Back-testing, previous trading and industry knowledge will be the best indicators for the length of time frame you should choose.
