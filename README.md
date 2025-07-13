# Analyzing-Amazon-Sales-Datam,.\
![Image Alt](https://github.com/ANNU-2484/Analyzing-Amazon-Sales-Data/blob/main/Screenshot%202025-06-19%20154415.png?raw=true)
Click the tale place right click new measurements 
//create new measure YTD Products Sold = TOTALYTD(COUNT(Amazon_Combined_Data[Product Category]),'Date Table'[Date])
//create a new measure YTD Reviews = TOTALYTD(sum(Amazon_Combined_Data[Number of  reviews]),'Date Table'[Date])
//create a new measure YTD Sales = TOTALYTD(sum(Amazon_Combined_Data[Price(Dollar)]),'Date Table'[Date])
//create a new measure QTD Sales = TOTALQTD(sum(Amazon_Combined_Data[Price(Dollar)]),'Date Table'[Date])
//create a new table Date Table = CALENDAR(MIN(Amazon_Combined_Data[Order Date]), MAX(Amazon_Combined_Data[Order Date]))
//create a new colom Date Table = CALENDAR(MIN(Amazon_Combined_Data[Order Date]), MAX(Amazon_Combined_Data[Order Date]))
//create a new colom Month Name = FORMAT('Date Table'[Date], "MMM")
//create a new colom Month Number = MONTH('Date Table'[Date])
//create a new colom Qtr = CONCATENATE("Qtr ",'Date Table'[Quarter Number])
//create a new colom Quarter Number = QUARTER('Date Table'[Date])
//create a new colom Week = WEEKNUM('Date Table'[Date])
this are showing like that 
![Image Alt](
