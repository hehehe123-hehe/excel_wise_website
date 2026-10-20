# [Use error handling features in Power Query to clean tables containing music data](https://www.wiseowl.co.uk/excel/exercises/standard/query-data/5448/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a blank Excel workbook and save it as Music Errors.xlsx.

Create queries to import the Album, Artist and Tour worksheets from the Music Tables.xlsx file from the folder shown at the top of this exercise.

Load each query into a table in a new worksheet.

Queries with errors in Power Query for Excel
You should spot a few issues with the imported data.

Edit the Album query to see what's wrong.

A column with errors in Power Query for Excel
Power Query added a step to change the data type of this column to a number, but not all of the values can be converted into numbers.

Add a step to replace errors in the US Billboard 200 peak column with null.

A column after replacing errors in Power Query for Excel
Check that the column no longer contains errors.

Apply a step to change the data type of the US Billboard 200 year end and US Sales (m) columns to a whole number.

Two columns with errors in Power Query
We broke it!

Insert a step before the Changed type step using Replace values to replace the offending character with an empty cell.

Columns after replacing values in a Power Query query.
We fixed it!

Edit the Tour query and select a cell containing an error to see what the problem is.

Reading error messages in a Power Query query.
These errors occurred in the original Excel file.

Use Replace Errors to fix this problem, changing errors to nulls in the Avg attendance and Avg ticket price columns.

Columns in Power Query after replacing errors.
Check that there are no errors remaining in the columns.

Edit the Artist query and change the data type of the Year disbanded column to a whole number.

A column containing errors in Power Query for Excel
There are more errors than useful data in this column.

Use a Remove Errors transform to leave only the valid rows in the query.

A Power Query table after removing error rows.
Some of the few remaining rows in the query.

Close and apply changes to the queries then save and close the Excel workbook.
