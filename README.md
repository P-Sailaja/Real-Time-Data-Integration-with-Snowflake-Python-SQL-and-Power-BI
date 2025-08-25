# End-to-End DWBI Project: Real-Time-Data-Integration-with-Snowflake-Python-SQL-and-Power-BI
--

<img width="1223" height="703" alt="BI Dashboard Image" src="https://github.com/user-attachments/assets/a849c922-0559-4b11-9a15-1d58f40edec2" />

--
🏢 **Business Case**

The organization sells thousands of products across hundreds of retail stores for the last 10 years.
It also runs a customer loyalty program to encourage repeat purchases.
The company wanted to:

- Integrate data from multiple sources (On-Prem DB, Excel, Sales files).

- Store & manage data in a central Data Warehouse (Snowflake).

- Generate insights about sales, customers, stores, loyalty programs, and categories.

- Build interactive dashboards for decision-making.

🛠 **Tools & Technologies**

- Python: Data extraction, CSV generation, transformation scripts.

- Snowflake: Cloud Data Warehouse for Fact & Dimension modeling.

- SQL: Queries for ETL validation, transformations, and business analysis.

- Excel: Reference data and source for dimensions.

- Power BI: Dashboard creation and reporting.

- Notepad++: For SQL & Python script editing.

🔑 **Steps & Workflow**

**Step 1:** Data Extraction & Transformation:

Used Python to extract data from On-Prem databases & Excel.

**Step 2:** Generated CSVs for:

- Historical Sales Data

- Dimensional Data (Customers, Products, Stores, Date, Loyalty Info)

- Last Month Sales Data

**Step 3:** Data Loading into Snowflake

- Used SnowSQL COPY command to load Fact & Dimension tables.

- Built Star Schema / Snowflake Schema for reporting.

📌 ERD Schema (Fact & Dimensions):

- FactOrders (OrderID, CustomerID, StoreID, ProductID, OrderDateID, etc.)

- DimCustomer (Name, Gender, DOB, City, Loyalty Info)

- DimProduct (Name, Category, Brand, Unit Price)

- DimStore (Store Details, Region, Manager)

- DimDate (Date, Month, Quarter, Year, Weekend Flag)

- DimLoyaltyInfo (Program Tier, Points Accrued)

**Step 4:** SQL Analysis & Business Logic

Wrote queries for:

- Total Sales, Discounts, Shipping Costs

- Customer Segmentation (Age Groups, Loyalty Tier)

- Regional and Store-Type Performance

- Category & Product Insights

**Step 5:** Visualization in Power BI

Connected Power BI to Snowflake.

Built interactive dashboard showing:

- KPIs → Total Sales, Orders, Customers, Avg Order Value, Discounts, Shipping

- Sales by Year, Region, StoreType

- Sales by Customer Age Group & Loyalty Tier

- Top Categories & Product performance

- Trends & Forecasts

📈 **Key Insights from Dashboard**

- Revenue Growth over the last 10 years with sharp increase in recent years.

- Outlet Stores & Exclusive Stores contribute highest sales (~29% and ~25%).

- East Region shows the highest revenue trend growth.

- Loyalty Programs → Platinum & Exclusive customers contribute maximum revenue.

- Young Customers (18–24) drive highest sales ($11.94M).

- Top Categories include Electronics, Health & Fitness, and Home & Furniture.
