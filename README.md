# stock-analysis
### Overview of Project
#### Purpose 
###### The purpose of this analysis was to provide Steve with the tools necessary to run a quick and accurante analysis on stocks from 2017 and 2018.Steve wants to run a stock analysis so that he can advice his parents on the best stocks to invest in. Steve's parents were most interested in the DQ stock, but since in 2018, it had a negative return of  *-63%* , Steve wants to run an analysis on all the stocks to figure out where his parents should invest. 

#### Analysis
###### In 2017, all the stocks except TERP had a positive return; however, in 2018 all the stocks, but 2 (ENPH and RUN), had a negative return. Taking a look at the two stocks that had positive returns both years, in 2018 ENPH was traded the most often and therefore had the highest Total Daily Volume for that year, while RUN was the third most traded stock. In 2017, neither RUN nor ENPH had the highest Traded Volumes, but they were both in the top 5 - ENPH was 5th and RUN was 4th.
![](https://github.com/gabrielavalos/stock-analysis/blob/main/Resources/All_Stocks_Analysis_2017.png)
![](https://github.com/gabrielavalos/stock-analysis/blob/main/Resources/All_Stocks_Analysis_2018.png)

#### Conclusion
###### ENPH and RUN are the two stocks Steve's parents should consider as investments because they both had positive returns in the past two years and were highly traded.

### Refactoring
#### Comparison
###### The refactored code ran faster than the original one for both 2017 and 2018.
![](https://github.com/gabrielavalos/stock-analysis/blob/main/Resources/2017.png)
![](https://github.com/gabrielavalos/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

![](https://github.com/gabrielavalos/stock-analysis/blob/main/Resources/2018.png)
![](https://github.com/gabrielavalos/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

 
### Summary
#### Anvantages
###### An advantage to refactoring is ending with a more efficient code. A more efficient code can be more dynamic and can execute at a faster speed. A major benefit to refactoring is in the way the developer thinks about the implementation of code, as the developer is improving the code she/him is also exercising the mind; therefore, thinking of new ways to program which can be implemented in future code. 

#### Disadvantages
###### A disadvantage to refactoring code is the risk in the process, a small change can create a chain of bugs that can be time consuming to solve; however, this is a trade-off of creating code that executes faster. refactoring does not open opportunities to add new functionality into an application

#### Application
###### How do these pros and cons apply to refactoring the original VBA script?
###### Our refactored code included a dynamic variable (tickerIndex), which enable VBA to loop through the whole data set just once for ALL tickers, instead of looping through all the data for EACH ticker. Once the tickerIndex is longer the same as the value in Cells(i,1), it adds 1 to the tickerIndex and compiles all the necessary data for the new ticker until the value in Cells(i,1) does again not match the current tickerIndex value, add 1 and proceeds with the next ticker. Looping through the data set just once and creating a more versatile variable (tickerIndex) significatly increased  execution speed. 
