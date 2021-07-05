# VBA_Challenge
## Stock_Analysis_With_VBA_and_Excel
Perforing Stock Analysis with VBA and Microsoft Excel

## Overview_Of_Project
  In this Project, we performed analysis of Stock Data for the years 2018 and 2017. After performing the analysis we edited or "refactored" the VBA code for the Stock Market Dataset to increase the efficiency of our code. Our target was to refactor the code so that it would loop through the data and collect the required information rathan than running individual loops for each individual stock.

# Results
  For our analysis, we looked at two factors: Total Daily Volume and Return. Total Daily volume, which is number of trades for a specific stock on a given day, is aggregated over the course of the year and Return, which is the percentage change in share price from the begining to the end of a given period, is calculated by taking the share price at the begining and end of the year and determining the percentage change. In addition, we have colour coded the percentage returns with a positive return donoted by the green colour while a negative change is denoted by the red colour.

The results of our anaysis has been summerized in two (2) tables below (refer to screenshot below):

<img width="226" alt="2017" src="https://user-images.githubusercontent.com/79813670/124403051-1bbd5c80-dd02-11eb-9ec1-eaf2c3a77356.png">

<img width="224" alt="2018" src="https://user-images.githubusercontent.com/79813670/124403052-1c55f300-dd02-11eb-9ac5-558903ab9001.png">

The edits to the VBA code that we performed helped to make the VBA script efficient and reduce run times. After we pushed our changes, the run times were significantly reduced.

<img width="291" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/79813670/124403083-72c33180-dd02-11eb-8fab-697872d20162.png">

<img width="282" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/79813670/124403091-82db1100-dd02-11eb-97e8-1a9b3e74e744.png">

  Based on the results of our analysis, it would seem to appear that there 2018 was not a good year for the stocks that we have picked. Given the volatile nature of the stock market, such a result may not be completely unexpected. However several companies suffered significant reduction in share prices which would suggest that these entities suffered fundamental issues which cannot be simply attributed to the volatility fo the market. On the other hand, the entities "ENPH" and "RUN" maintained healthy increases in share price over multiple years which would suggest these two companies have performed well on fundemental metrices and the market has responded accordingly.
  
# Summary
  
  Refactoring code is a generally beneficial process which can change the way that code is designed and implemented. The goal with refactoring is typically to improve readability and effeciency by streamlining the code to reduce the number of tasks the code has to perform. Howevver there are some disadvantages to refactoring. In cases where the original construction and subsequent refactoring are done by individuals, understanding and debugging could become difficult or hard understand.
  Refactoring the original VBA script here provided the advantage of speed since the code no longer has to run multiple loops over the same data. In this way, if the data set is expanded by adding multiple worksheets for multiple years, the script can still run and provide meaningful analysis without much delay.
