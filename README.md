# Sales-Shipping-Dashboard

An Interactive dashboard showing the sales and shipping year on year for a country. 

![image](https://github.com/archishmanSingha/Sales-Shipping-Dashboard/assets/123219771/265d9abb-599e-44c1-b459-9872c93211e7)

Visualization is done in Excel using latest tools such as Power Query to connect to multiple CSV files which contained data for the country of each year,and then was used to clean, shape and restructure the data. Ltaer, I used PowerPivot to create advanced data models, powerful calculations and generate interactive charts. 

The visualization is done in such a way that it is easily understandable for quick analysis and decisions.

Power Query is used to import and load the data, added new columns such as "Sale Amount" ( by multiplying columns order quantity, Unit sell price, discount, rounded the value to two decimal places ) and  "Ship date" ( by subtracting dates order date from ship date ). Also removal of unwanted columns, checked and set the datatypes correctly were few of the tasks perfomed using Power Query. 
Power Pivot is used to manage tables such as category information,customer information etc and add them to the data model, then we created relationships between those tables with sales data, and also set the sort order. Also used Power Pivot Measure to add new field lists in different instances.

I created different Pivot Tables from Pivot Chart fields and later visualized them using charts such as bar charts and line charts. 
For better visualization, since we have location fields in the dataset hence, Maps Charts have been added for showing shopping and sale data.
Sparklines were used using OFFSET function for better visualization.

Slicers have been added for better filteration throught the Dashboard for more insightful analysis from charts and tables.

Additional data for the upcoming years can be updated into the dashboard without any modification, just by adding the file to the folder from which Power Query is importing the data
