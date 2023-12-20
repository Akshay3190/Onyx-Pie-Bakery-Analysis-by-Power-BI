# Onyx-Pie-Bakery-Analysis-by-Power-BI
<br>
Analyzed the 3-year data data of Onyx Pie Bakery.
<br>
Data Cleaning Process-
<br>
Removed columns – Month/Yr & Day of Week
<br>
Created new dimension tables for -
<br>
Pie Flavor, Slice Or Whole Pie, Pre-Order/In-Store Purchase & Organic?
<br>
Removed columns “Pie Flavor”, “Slice of Whole Pie”, “Pre Order/In-store purchase”, and “Organic” from Fact Table as we already have their respective ID Table.
<br>
Brought all 4 ID tables at the start of the Fact Table. The first column should be “Order ID”.
<br>
Added 5-6 columns in the Calendar Table with date, weekdays, month, month  no, Quarter, and quarter number to get specific insights.
<br>
Data Modelling-
<br>
The relation of each table is one to  many  (1 to *) which means the Dimension table has only one entry from the dimension table & there are many such entries to  its relation to data in the Fact Table. Connected the Date table with the Fact table in the data modeling section by simply dropping the date from the Date table to the Order date of the Fact table.
![Data Modelling](https://github.com/Akshay3190/Onyx-Pie-Bakery-Analysis-by-Power-BI/assets/149465028/ab34b7f0-98f9-4ce4-b04f-2909e84f0b95)
<br>
![image](https://github.com/Akshay3190/Onyx-Pie-Bakery-Analysis-by-Power-BI/assets/149465028/e427225d-5e2d-4eed-b931-9fed17895a55)
<br>
Visuals like Donut charts, Bar charts, line charts & KPIs were added to get the insights. 3 types of slicers are used like Pie Size, Order Type, and Year to get specific details.




