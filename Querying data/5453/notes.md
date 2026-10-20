# [Duplicate and append queries in Power Query to add multiple worksheets to a single list.](https://www.wiseowl.co.uk/excel/exercises/standard/query-data/5453/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a new Excel workbook and save it as Appending Albums.xlsx.

Choose to import data from the Album Sales.xlsx workbook from the folder shown at the top of this exercise.

Select only the 20-29 million worksheet and when loading the data choose to create a connection only.

Creating a connection only query in Power Query for Excel
Don't load the data into Excel yet.

Edit the query in Power Query and add the following steps:

Remove the Ref. column.

Rename the Reported sales* column to remove the asterisk.

Add a custom column called Years since release using the formula shown below:

A custom formula in Power Query calculating the age of albums
Try not to feel old when you see some of the results.

Here's what the data should look like at this stage:

A query table with several transforms in Power Query for Excel
So far, so good.

Duplicate the query and rename it as 30-39 million.

Edit the Navigation step of the duplicated query to extract the data from the 30-39 million worksheet.

Editing the Navigation step of a Power Query query 
It's probably easiest to edit the sheet name in the formula bar.

If you edit the Navigation step using the dialog box rather than the formula bar, watch out for extra steps that Power Query inserts automatically! You may need to remove an extra Promoted Headers and Changed Type step.

From the Home tab in the ribbon choose Close & Load To... and create a connection only.

Open Power Query and duplicate the original query again. Use the duplicated query to extract data from the 40 million plus worksheet.

Multiple duplicated queries in Power Query
You should have three queries performing the same transforms on different data sets.

Close and load this query, again choosing to create a connection only.

Now you can append all three queries into a single list. Open Power Query again and from the Home tab of ribbon click the dropdown arrow next to Append Queries and choose Append Queries as New.

Appending queries in Power Query for Excel
Append all three queries in the dialog box.

Rename the query as Top Selling Albums and close and load the results to a table in a new worksheet.

A set of queries in Power Query for Excel
Only the Top Selling Albums query should be visible in a worksheet.

Save and close the workbook.
