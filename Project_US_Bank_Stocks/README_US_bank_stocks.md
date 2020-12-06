# US Bank stocks gain and loss from 2006-2020.
> The study objective: Idnetification of the riskiest bank stocks.   
Approach: a- Acquisition of data from Yahoo Finance, b- iplot and other data visualizations.


## Table of contents
* [General info](#general-info)
* [US Bank Stocks](#image)
* [Packages and approaches](#R)
* [Status](#status)
* [Inspiration](#inspiration)


## General info
Analyses on the US bank stocks from 2006 - 2020.

## US Bank Stocks
In 2008 and 2009 we see the loss of several banks, interestingly part of the loss was on the inaguration time.

score.org
![US-bank_stock](./static/profitloss.jpg) 

## Example Packages/Libraries
numpy, Pandas, matplotlib, seaborn, plotly


#### Code Example - Acquisition of JPM data
	start = datetime.datetime(2006, 1, 1)
  	end = datetime.datetime(2020, 12, 1)
 	JPM = data.DataReader("JPM", 'yahoo', start, end)
	
 
## Status
Project will be revisited for the next year data.

## Inspiration
Using data visualization tools to learn more about the rik nature of the bank stock data in US.
