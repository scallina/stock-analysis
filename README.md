# stock-analysis

## Project Overview

This project was initially created to assist my client, Steve with an analysis of several Green stocks' performance over the 2017 and 2018 trading years. 
After the first draft of the project, I refactored existing code to perform more efficiently in the case Steve should want to analyze much larger lists of stocks. 

## Results
Time to run initial Subroutine for 12 stocks
- year 2017: .23 seconds

![image](https://github.com/scallina/stock-analysis/blob/main/Green_Stocks_Timer_2017.png)
- year 2018: .29 seconds

![image](https://github.com/scallina/stock-analysis/blob/main/Green_Stocks_Timer_2018.png)

Time to run refactored Subroutine for 12 stocks
- year 2017: .09 seconds 

![image](https://github.com/scallina/stock-analysis/blob/main/VBA_Challenge_2017.png)
- year 2018: .08 seconds

![image](https://github.com/scallina/stock-analysis/blob/main/VBA_Challenge_2018.png)

## Summary

### Advantages of refactoring code:
Refactoring code is a helpful way to improve on existing work without having to recreate the general logic of a subroutine. It allows teams to check and improve on the work of individual team members and suggest more efficient ways to approach the same problem. 

Refactoring code may prove disadvantageous if it is not well commented or the teams don't communicate well about the general purpose of the project. 

### Notes on original VBA script vs refactored script. 
The refactored script will prove more advantageous if Steve chooses to use it for larger sets of stocks being analyzed over multiple years. In it's, the nested loop will save Steve exponential amounts of time as he uses this subroutine to analyze larger pools of stocks over multiple years. 

A disadvantage of the refactored script would become clear if Steve were to use this subroutine on a larger pool of stocks (e.g., a list of 100 stocks). 
Steve would need to either: 1) create a for loop that would automatically update the tickers array before running the analysis or 2) manually adjust the array to include the 100 stocks he wishes to analyze. This could be the focus of a future refactor if this subroutine were to be used in the future. 

