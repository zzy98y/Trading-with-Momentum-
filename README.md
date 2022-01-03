# Trading-with-Momentum-

## In this project, we're developing a trading strategy that deal with momentum. 


In this project, we will be looking into S&P 500 stocks - Apple Inc. 

## Resample Adjusted Prices 
When we develop trading signal, it's not always base on the daily prices, sometimes we can change it to different frequency to help develop 
more efficient trading signal (month, week etc..) 

## Compute Log Return 
In this project, we want to use log return for our momentum indicator. 

## Shift Returns 
We shift return to compare the previous returns to future returns. 

## Generate Trading Signal 
A trading signal is a sequence of trading actions, or results that can be used to take trading actions. 
A common form is to produce a "long" and "short" portfolio of stocks on each date (e.g. end of each month, or whatever frequency you desire to trade at). 
This signal can be interpreted as rebalancing your portfolio on each of those dates, entering long ("buy") and short ("sell") positions as indicated.
In this project, we want to use return generalize whether to "long" or "short" a stock. 

## Projected Returns 
We use the stock we have selected from the previous section and project whether the stock has the potential to be profitable. 

## T-test 
We can use T-test to help check whether in a more generalized sense, the strategy we developed is profitable or not. 

