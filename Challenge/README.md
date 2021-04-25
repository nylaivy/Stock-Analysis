#Stock Analysis

##Overview Of Project
The purpose of this project was to use stock data to find the total daily volume and yearly return for each stock as a means of evaluating how active each of these stocks were traded in both 2017 and 2018. Daily volume is the total number of shares traded throughout the day; it measures how actively a stock is traded. If a stock is traded often then the price will accurately reflect the value of the stock so summing up the daily volume for each year will give us the yearly volume and a rough idea of how often the stock gets traded. The yearly return is the percentage difference in price from the beginning of the year to the end of the year. This shows how much an investment in a particular stock would have grown or shrunk in a particular year.

##Results
Majority of stocks had a negative yearly return in 2018 versus 2017. We see that 10 of 12 stocks analyzed (approximately 83% ) had a negative yearly return in 2018 compared to only 1 of 12 of these same stocks (approximately 8%) in 2017 having a negative return. A screenshot of these results from the analysis can be seen below. 

![2017_Analysis](/Challenge/Resources/2017_Analysis.png)
![2018_Analysis](/Challenge/Resources/2018_Analysis.png)

If anyone were to invest in any of these stocks throughout both of these years they should not invest in “TERP”. They should also invest in “SEDG” in 2017 as it had the highest yearly return, as well as investing in “RUN” in 2018 for the same reason. There does not seem to be a correlation between total daily volume for a given year and yearly return as the stock with the highest total daily volume was not the stock with the highest return in 2017 and the stock with the lowest total daily volume was not the stock with the lowest return in both 2017 and 2018. In addition to this, there were relatively high total daily volumes for many of the stocks in 2018 compared to 2017 but majority of these stocks had a negative return.

The execution time of the original script was about 0.25 seconds for both 2017 and 2018, while the execution time of the refactored script was about .07 seconds for both 2017 and 2018. This can be seen in the screenshot of the pop-up message when running the macros for both analyses below. Clearly the refactored code is much faster with the use of arrays and loops to complete the same analysis done originally.

![VBA_Challenge_2017](/Challenge/Resources/VBA_Challenge_2017.png)
![VBA_Challenge_2018](/Challenge/Resources/VBA_Challenge_2018.png)

##Summary
An advantage of refactoring code is that doing so allows for code written for a specific scenario to apply to more expanded scenarios. A disadvantage of refactoring code is that it can sometimes be more confusing when you are not writing code from beginning to end yourself because you have to understand code written by someone else before refactoring it.

For this specific VBA code refactoring allowed for the original code written to not only be changed into something that could be applied to more stocks but also with a faster execution time. The disadvantage mentioned above does not apply for this specific scenario because the original code that was then refactored was written by the same person. However, another disadvantage for this refactored code specifically is the simple fact that it was a bit more complicated to write as more loops and arrays were needed to do so.
