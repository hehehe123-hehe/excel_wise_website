# [Create custom columns to calculate new values from a data source of music.](https://www.wiseowl.co.uk/excel/exercises/standard/query-data/5447/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a blank Excel workbook and save it as Music Custom Columns.xlsx.

Create a query to import the Artist and Tour worksheets from the Concert Tours.xlsx file from the folder shown at the top of this exercise. Load each query into a table on a new worksheet.

Edit the Tour query and add a custom column called Tour years which calculates how many years each tour spanned.

A custom column in Power Query for Excel
Subtract the Start year from the End year and add 1 to the result.

Add more custom columns to calculate the following values:

Column name

What it should do

Shows per year

Divide Shows by Tour years

Avg show revenue

Divide Actual gross by Shows

Avg attendance

Divide Attendance by Shows

Assign an appropriate data type to each of the new columns.

A set of custom columns in a Power Query query
You could use the Number.Round function to control the number of decimal places.

Add a conditional column called Duration which tests if the Start year is equal to the End year. If so, return Single year, otherwise return Multi year.

A conditional column in Power Query for Excel
Some of the results you should see.

Add a conditional column called Crowd size which tests the value of the Avg attendance column according to the following rules:

Avg attendance

Result

Is null

Unknown

Less than 25,000

Small

25,000 to less than 50,000

Medium

Anything else

Large

Check that the column returns the correct value.

Results of a conditional column in Power Query for Excel
Some of the results you should see.

Edit the Artist query and add a custom column which concatenates the Artist and Type columns as shown in the image below:

A concatenated column in Power Query for Excel
You can use the Text.Lower function to change a string to lowercase.

Add a column to concatenate the Artist and Year formed columns as shown in the image below:

Concatenating text and numbers in Power Query
You may find the Number.ToText function useful in this example.

Close and load the changes to the queries and then save and close the file.
