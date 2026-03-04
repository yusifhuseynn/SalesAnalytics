📊 Sales Analytics — Excel Dashboard

An interactive Sales Dashboard built with Excel using Power Query, PivotTable, and Charts — from raw data to fully functional business intelligence.


📁 About the Project
This project transforms 9,994 rows of raw sales data into a fully functional, interactive Excel Dashboard.
It covers sales of office supplies, furniture, and technology products across various US states between 2014 and 2017.

📌 Dataset Structure
ColumnTypeDescriptionOrder DateDateDate of the orderCustomer NameTextFull name of the customerStateTextUS stateCategoryTextProduct category (3 types)Sub-CategoryTextSub-category (17 types)Product NameTextFull product nameSalesDecimalSales amount (USD)QuantityIntegerOrder quantityProfitDecimalProfit amount (USD)

🛠️ Technologies Used
ToolPurposeMicrosoft ExcelMain working environmentPower QueryData loading, cleaning and transformationPivotTableMulti-dimensional analysis and groupingPivotChartVisual presentation (Bar, Line, Pie, Area, Map)SlicerInteractive filters (Category, Year)

🚀 How to Use
1. Download the dataset
Download the salesdata.csv file from this repository
2. Open in Excel
Excel → Data → Get Data → From File → From Text/CSV
→ Select salesdata.csv → Transform Data
3. Prepare in Power Query

Set column types (Date, Decimal, Whole Number)
Add year column: Add Column → Date → Year
Add month name: Add Column → Date → Month → Name of Month
Click Close & Load to load the table

4. Build PivotTables
Create separate PivotTables for each analysis:
SheetRowsValuesCustomer SalesYearSum of SalesState SalesStateSum of SalesTop 5 CustomersCustomer NameSum of ProfitAnnual ProfitYear × CategorySum of ProfitMonthly SalesMonth NameSum of Sales
5. Create Charts

Select the appropriate chart type for each PivotTable
Use a consistent color scheme: #1e3a5f · #2d6a9f · #e67e22

6. Build the Dashboard

Create a new sheet → name it Dashboard
View → Gridlines → turn off
Move all charts to this sheet
Add Insert → Slicer for Category and Year filters
Connect each Slicer to all PivotTables via Report Connections


📊 Dashboard Features

✅ Sales analysis by product and category
✅ Geographic map by US state
✅ Monthly and annual trend charts
✅ Top 5 customers profit analysis
✅ Profit dynamics over time
✅ Interactive Category and Year filters


📈 Key Insights
MetricValueTotal Orders9,994Total Sales$2.30MTotal Profit$286,397Profit Margin12.5%Best-selling productPhones ($330K)Top sales stateCalifornia ($55K)Peak monthNovember ($352K)
