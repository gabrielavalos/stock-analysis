# stock-analysis
### Overview of Project
#### Purpose 
###### The purpose of this analysis is to provide Steve with the necessary tools to run a quick and accurante analysis on stocks. Steve wants to run a stock analysis so that he can advice his parents on what stocks to invest in. Steve's parents are most interested in the DQ stock, but in 2018 it had a negative return of  *-63%*, so now, Steve wants to run an analysis on all the stocks to figure out which ones his parents should invest in. 

#### Analysis
###### In 2017, all the stocks except TERP had a positive return; however, in 2018 only ENPH and RUN had a positive return. In 2018 ENPH was the most traded stock; therefore, it had the highest Total Daily Volume for that year, while RUN had the third highest Total Daily Volume. In 2017, neither RUN nor ENPH had the highest Total Daily Volume, but they were both in the top 5 - ENPH was 5th and RUN was 4th.
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
###### An advantage to refactoring is ending with a more efficient code, which is more dynamic and executes faster. Another major benefit to refactoring is to the developer, as she/he develops new skills that will improve future code.

#### Disadvantages
###### A disadvantage to refactoring code is the risk of breaking the code - one small change can create a chain of bugs that can be time consuming and difficult to solve. Additionally, the developer can have a difficult time understading the code being refactored, which would make the process very frustrating and somewhat impossible.

#### Application
#### Pros
###### Our refactored code included a dynamic variable (tickerIndex), which enables VBA to loop through the data set just once for ALL tickers, instead of looping through all the data for EACH ticker. Once the tickerIndex is no longer the same as the value in Cells(i,1), it adds 1 to the tickerIndex and compiles all the necessary data for that ticker until the value in Cells(i,1) no longer matches the current tickerIndex value, adds 1 again and proceeds with the next ticker. Looping through the data set just once and creating a more versatile variable (tickerIndex) significatly increased  execution speed. Additionally, I was able to see a new way of looping through data (with the tickerIndex), so it is something I can apply to future code.

#### Cons
###### At first, it was really difficult to understand the changes we were making - it seemed that by adding the tickerIndex variable we were adding an extra step. Additionally, the totalVolumes valuese kept overflowing, a bug that took me some time to fix.
