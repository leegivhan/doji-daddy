# doji-daddy
Doji stock finder and stock tracker

Potential Tech Stack: TypeScript, Bootstrap, PostGreSQL, Docker

What site does: Finds Doji stocks and tracks up to 10 stocks

Allows user to login

Website displays:

## Procedure for doji finder
1. Look for stock in previous closing day where the opening price is 0.5 points or less different than the high or low price.
1. If the difference between the lowest high of that stock in the previous week and the highest high from the previous week is 10 points or greater, add it to database of dojis from the previous day.
1. Repeat for all relevant stocks and display them on the site.

## Stock tracker
For each of up to 10 stocks
* Return the top 3 highs of the year
* Return the top 3 highest lows of the year
* Return the top 3 highest opening prices of the year
* Return the top 3 highest closing prices of the year 
