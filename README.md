# All Stocks Analysis
Performing analysis on the stock performance in 2017 and 2018.

## (1) Overview of Project
To show the yearly return of all the stocks in 2017 and 2018, in order to show the growth of each stock throughout the year and be able to do a comparison between their performance in both 2017 and 2018.

## (2) Results
The return column shows the yearly return of each stock in each year. The calculation was based on the percentage changes between the starting price and ending price of each stock. 
 
In the 2017 result, we can see that it was a positive year, where almost all, except TERP, had positive returns. Stocks such as DQ, ENPH, FSLR, and SEDG went above and beyond with more than 100% return. However, when it came to 2018, besides ENPH and RUN, all stocks went negative with their yearly return rate. By comparing the total daily volume, we could see the numbers of trade dropped significantly from 2017 to 2018. This may show how investors were not being confident with the market in 2018. 

![image](https://github.com/sunnycywong/Module-2_stock-analysis/blob/main/Resources/VBA_Challenge_2017.png) 

![image](https://github.com/sunnycywong/Module-2_stock-analysis/blob/main/Resources/VBA_Challenge_2018.png) 

## (3) Summary

### <ins> *The advantages and disadvantages of refactoring code in general* <ins> 
 
The refactoring code enables us to easily pull out data both years, whereas, the original one was only showing one year. 
The downside of this code is not able to compare both years side by side. The report user would need to hop in between the two years to do the analysis. Taking screenshots of each result could be an alternative. But ideally, it would be nice to have both years to be set side by side.  

 
### <ins> *The advantages and disadvantages of the original and refactored VBA script* <ins> 
 
Both the original and refactored VBA script were well organized, which would make it easier to see the workflow and what is being set for the macro. Yet, when comparing the two scripts. It would be questionable whether using “j” for the second loop in the original script is necessary since the coding would still work with keeping “I”. It might be a good practice to use a different assignment statement for each loop to make it easier for reading through the script and understand the flow. 
