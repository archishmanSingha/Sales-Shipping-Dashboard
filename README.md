# Sales-Shipping-Dashboard

An Interactive dashboard showing the sales and shipping year on year for a country. 

![image](https://github.com/archishmanSingha/Sales-Shipping-Dashboard/assets/123219771/265d9abb-599e-44c1-b459-9872c93211e7)

Visualization is done in Excel using latest tools such as PowerQuery to connect to multiple CSV files which contained data for the country of each year,and then was used to clean, shape and restructure the data. Ltaer, I used PowerPivot to create advanced data models, do powerful calculations and generate interactive charts. 

The visualization is done in such a way that it is easily understandable for quick analysis and decisions.

Maps have been added showing shopping and sale data.
Slicers have been added for better filteration.

PowerQuery is used to load the data, added new column "Sale Amount" by multiplying columns order quantity, Unit sell price, discount, rounded the value to two decimal places. Added another column "Ship date" by subtracting dates order date from ship date, removed unwanted columns, checked and set the datatypes correctly

PowerPivot is used to manage tables such as  category information,customer information and add to data model, then we created relationships between those tables with sales data, setting the sort order.

I created different Pivottables from pivotchart fields and later visualized them using charts such as  bar chart, line chart. Also used PowerPivot Measure to add new field list in different instances.

Also included Map Charts, sparklines using OFFSET
Added slicers to filter charts and tables.

Additional data for the upcoming years can be updated into the dashboard without any modification.
