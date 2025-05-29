# Blinkit_db-project

🧹 1. Data Cleaning:
The initial phase of the project focused on cleaning the Item_Fat_Content field to ensure data consistency. Variations such as "LF" and "low fat" were standardized to "Low Fat", and "reg" was standardized to "Regular". This step enhances data quality, enabling accurate reporting and aggregation.

📊 2. KPI Calculation:
Several key performance indicators (KPIs) were calculated to assess the platform's overall performance:
Total Sales in millions
Average Sales per item
Total Number of Orders
Average Rating across all products
These KPIs provide a quick snapshot of the platform's sales efficiency and customer satisfaction.

📈 3. Sales Analysis by Category:
a. Sales by Fat Content:
Calculated total sales grouped by the standardized Item_Fat_Content categories. This analysis helps identify customer preferences between low-fat and regular products.
b. Sales by Item Type:
Grouped total sales by Item_Type and ordered them in descending order to highlight top-performing product categories on the platform.

🧾 4. Advanced Reporting Using SQL Pivot and Aggregations:
a. Fat Content Sales by Outlet Location:
Used a PIVOT operation to display sales distribution of fat content (Low Fat vs. Regular) across different Outlet_Location_Types. Replaced nulls with zeros for clarity and better readability.
b. Sales by Establishment Year:
Analyzed how outlet age (based on Outlet_Establishment_Year) correlates with sales performance, helping identify trends tied to outlet maturity.
c. Sales Contribution by Outlet Size:
Applied window functions to calculate percentage contribution of each Outlet_Size category to the overall revenue. This provides insight into the impact of small, medium, and large stores on total sales.

🗺️ 5. Regional and Outlet-Level Analysis:
a. Sales by Outlet Location Type:
Grouped sales by Outlet_Location_Type to understand the geographic distribution of revenue.
b. Comprehensive Metrics by Outlet Type:
Aggregated multiple metrics—total sales, average sales, order count, average rating, and item visibility—grouped by Outlet_Type. This enables evaluation of how different outlet types perform across key dimensions.

