# API Mini Project


## Problem
Using the Quandl API, the stock prices of a company called Carl Zeiss Meditec were analyzed. The company manufactures tools for eye examinations, as well as medical lasers for laser eye surgery

1. Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).
2. Convert the returned JSON object into a Python dictionary.
3. Calculate what the highest and lowest opening prices were for the stock in this period.
4. Calculate the largest change in any one day (based on High and Low price)?
5. Calculate the largest change between any two days (based on Closing Price)?
6. Calculate the median trading volume during this year. 

## Approach

1. Used the requests package to call the Quandl API
2. Converted json text to a dictionary
3. Used nested for loops to search through dictionary to calculate stock price changes and averages.



## Deliverables
1. Data wrangling code in Python notebook.
