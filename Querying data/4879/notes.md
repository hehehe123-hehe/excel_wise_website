# [Tidy up exchange rate and investment data in Power Query, splitting columns and replacing values.](https://www.wiseowl.co.uk/excel/exercises/standard/query-data/4879/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
In a new workbook, use Power Query to load data from the Exchange Rates table in the Tables workbook:

Exchange rates table
Initially the data looks like this.

Use Get Data to load this into a new Excel workbook, splitting the currencies:

Exchange rates loaded
As a bonus task, filter the data to exclude the (pointless) GBP to GBP exchange rate.

Too easy?  Load data from the Share Prices worksheet in the Tables workbook:

Investments data
The investment symbol needs splitting out, and the price should be numeric.

 

Split the investment into the name and code, and make the price into a number, to get something like this:

Loaded share price data
Investments sorted by the Change column, with the highest value first. You should filter the table in Power Query to omit any investments whose prices contain $ or € symbols.  You can type in a € by pressing Alt + Ctrl + 4.

Save this workbook as Splitting Shares, then close it down.
