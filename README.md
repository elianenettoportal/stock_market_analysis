# stock_market_analysis
ETL - ML - Stock Market Analysis

This is just a personal project to learn about Machine Learning, Python development and Stock Market. I did a search in a Brazilian website named Ocean14 (https://www.oceans14.com.br) that resums the brazilian stock market, all the stocks listed in B3 the Stock Exchange. 

My choice was for a Regression Linear analysis, that predicts a continuous number, for this I am looking into Dividend Yeld a target value, or, a value I want to explain and predict in the future. It is a dependent variable for the machine learning.

The data used to feed the models comes from a webscraping code that I did. It reads a scoreboard of dividends with stocks indicators from 1998 to 2022(Today) of a few stocks.

## What is Dividend Yield
Dividend yeld represents the ratio between the dividends paid over the course of 1 year of the stock price.
It matters to anyone who wants to have a long-term passive income. It is a solid growth analysis.
Dividend yeld will be the dependent variable, let's see how much it depends on the others for a change

## ETL & Webscraping 
The webscrape code grabs the indicators from a scoreboard in Ocean14 of stocks listed in Brazilian´s capital marcket.
The code will request(execute a endpoint request) for Indicators. The scoreboard in oceans14 list all stock indicators from 2002 to 2022 (current year of this document)

## Machine Learning (Regression)
A Regression Linear predicts a continuous number, for this analyse we are looking into Dividend Yeld, that will be our target value, a value we want to explain and predict in the future, on my end, it is a dependent variable.

4 Machine Learning:
1) Decision Tree Regression:
  The model evaluated pretty good getting a return of 97% of accuracy when predicting divident yeld for future

2) Random Forest Regression:
  The model evaluated pretty good getting a return of 99% of accuracy when predicting divident yeld for future

3) Multiple Linear Regression:
  The model evaluated badly getting a return of 65% of accuracy when predicting divident yeld for future

4) Support Vector Regression:
  The model evaluated poorly getting a return of 10% of accuracy when predicting divident yeld for future

4) Polynomial Regression:
  The model evaluated very badly and it was not able to get a return


