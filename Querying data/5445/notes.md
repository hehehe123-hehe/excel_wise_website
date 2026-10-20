# [Use Power Query to clean data sources related to music.](https://www.wiseowl.co.uk/excel/exercises/standard/query-data/5445/)

Create a blank Excel workbook and save it as Transforming Music.xlsx.

Choose to import data from the Concert Tours.xlsx file in the folder shown at the top of this exercise.

Load the Highest grossing tours and Most attended tours worksheets to tables in separate worksheets.

A list of queries in an Excel workbook
You should have two queries loaded into separate worksheets.

Edit the Highest grossing tours query in Power Query.

Add a step to remove the first row from the table.

A data table in Power Query for Excel
The first row is empty so we don't need it.

Delete the Ref column, then move the Artist and Tour title columns to the right of the Peak column.

Multiple columns in Power Query for Excel
Put the first four columns in this order.

Remove the $ sign from the Actual gross, Adjusted gross and Average gross columns and make sure the data type of each is set to Whole number.

Number columns in a query in Power Query for Excel
You can quickly remove the $ symbol using a Replace Values transform.

Remember that you can select multiple columns to apply the same to transform to several columns at once.

Split the Year column into two separate columns called Start year and End year.

A column in Powe Query after a split column transform
You can create these columns in many different ways, choose your favourite!

Close and load the changes you've made to the Highest grossing tours query.

Now edit the Most attended tours query, performing the following transforms:

Remove the Ref column.

Split the Year(s) column into a Start year and End year column.

Modify the Tickets sold column to return only the number of tickets.

Filter the table for tours which started after the year 2020 and had at least 100 shows.

Close and load the changes to the query.

An Excel table created from a query in Power Query.
The results you should see.

Close and save the file.
