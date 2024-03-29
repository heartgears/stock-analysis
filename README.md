# stock-analysis
## Overview
The purpose of this analysis was to help Steve make informed decisions in the stock market regarding a particular set of stocks. By comparing the stock DQ against other similar stocks, we can see if it is a worthwhile investment for Steve's parents.

## Technologies and Requirements
* Software: Microsoft Excel
* Coding Languages: VBA

## Results
The stock that Steve's parents chose was not a strong performer in the market, they would be better off choosing a different stock to invest in, like ENPH, which had the strongest performance of the group considering both 2017 and 2018. While the sock market overall had poor performance in 2018, ENPH delivered the second best return of the group at 81%, just behind RUN at 84%. The year prior, EPH had the third best return of the group, increasing by more than 100%, while the two stocks that outperformed it in 2017 would lost value the following year.

![2017](2017_stock.png)
![2018](2018_stock.png)

### Code Deliverables
* The tickerIndex is set equal to zero before looping over the rows
* Arrays are created for tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrices
* The tickerIndex is used to access the stock ticker index for the tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrices arrays
* The script loops through stock data, reading and storing all of the following values from each row: tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrices 
* Code for formatting the cells in the spreadsheet

## Summary
### What are the advantages or disadvantages of refactoring code?
Refactored code runs more efficiently than non-factored code, and is easier to read and edit. This is especially useful when working with larger datasets, as it will save time on executing the code. While it is however, a tedious and sometimes confusing process, it ultimately saves time in the long run. 

### How do these pros and cons apply to refactoring the original VBA script?
Saving time on fractions of a second isn't practically useful, so the strongest reason to refactor the code in this instance would be to make it more legible and editable. If someone were to want to make edits to this code or build upon it, having the code be as clean and succinct as possible will make it easier to work on as well.
