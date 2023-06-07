# Sales-Shipping-Dashboard

An Interactive dashboard showing the sales and shipping year on year for a country. 

Analysis is made using Latest tools such as PowerQuery to extract data and PowerPivot to analyze. Easy to read Tables for quick decisions.
Maps have been added showing shopping and sale data.
Slicers have been added for better filteration.

PowerQuery is used to load the data, added new column "Sale Amount" by multiplying columns order quantity, Unit sell price, discount, rounded the value to two decimal places. Added another column "Ship date" by subtracting dates order date from ship date, removed unwanted columns, checked and set the datatypes correctly

PowerPivot is used to manage tables such as  category information,customer information and add to data model, then we created relationships between those tables with sales data, setting the sort order.

I created different Pivottables from pivotchart fields and later visualized them using charts such as  bar chart, line chart. Also used PowerPivot Measure to add new field list in different instances.

Also included Map Charts, sparklines using OFFSET
Added slicers to filter charts and tables.

Additional data for the upcoming years can be updated into the dashboard without any modification.
