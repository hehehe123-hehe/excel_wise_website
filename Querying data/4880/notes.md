# [Create a query to import a table of tall buildings, create new columns and then pivot the data.](https://www.wiseowl.co.uk/excel/exercises/standard/query-data/4880/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a new Excel workbook, and create a query based on the Tallest buildings worksheet in the Tables workbook in the above folder.

Apply transforms and create a new Metres per floor column to get this:

New building data
Use the pinnacle height to get the height in metres and feet, and remove the roof height column.

Warning: the character before the m and ft at the end of the height in metres and feet doesn't seem to be a space.  Your best bet is to remove the m and ft, and then apply the Trim transform (if you can find it, that is).

Now get rid of all but these 3 columns:

Final 3 columns
You'll also need to remove any buildings with null completion years, and sort by the completion year.

Create a pivot transform to show the number of buildings by country and completion year:

Pivoted data
The first few countries and years that you should see.

Load this data into your Excel workbook, then save your workbook as But why, and close it down.
