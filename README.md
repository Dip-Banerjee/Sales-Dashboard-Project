Dataset Name: Sales Dataset
Source: Kaggle
Description: The dataset contains sales records including Order Date, Region, Product, Sales, Customer Details, and Shipping Information.
1️⃣ Data Cleaning & Preprocessing in Excel
🔹 Challenges Faced:
Date Format Issues: Some dates were stored as text instead of date format.
Data Type Inconsistencies: Certain numerical columns were stored as text.
Sorting & Filtering Issues: Some records didn’t follow the correct format.
🔹 Solutions Implemented:
Used DATEVALUE() and VALUE() functions to convert text-based dates into proper date format.
Checked for blank cells, duplicates, and inconsistencies before using the dataset in Power BI.
Created a Pivot Table to analyze monthly and yearly sales trends.

2️⃣ Trend Analysis & Pivot Table in Excel
Built Pivot Tables to summarize sales by Region, Category, and Year.
Created a Line Chart to visualize sales trends over time.
Applied grouping on date columns to analyze monthly and quarterly sales.

3️⃣ Power BI Dashboard Creation
🔹 Key Visualizations:
✅ Sales Trend Analysis: Line chart showing sales growth over the years.
✅ Top & Bottom Performers: Bar chart displaying top-selling products.
✅ Region-wise Sales: Filtered breakdown of sales performance by region.
✅ Category Filter: Added an interactive slicer for Furniture, Technology, Office Supplies.
✅ Sales KPI Card: Dynamic metric showing total sales for easy reference.

🔹 Challenges Faced:

Hidden Columns Issue: Some fields were not visible in Power BI after importing the dataset.
Date Hierarchy Problems: Power BI was not recognizing date columns properly.
Filter Issues: Selecting one filter unchecked another (Fixed by enabling multi-select).
🔹 Final Enhancements:

Improved the dashboard UI with clear labels, formatting, and color scheme.
Published the report to Power BI Service and created a public link for sharing.
