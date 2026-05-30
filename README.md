# 🏡 Real Estate Sales Analytics Dashboard
## 📌 Project Overview
This project analyzes the commercial performance of a real estate company using Power BI, applying data modeling, DAX measures, time intelligence, and cohort analysis.

The objective is to transform transactional data into strategic insights that support executive decision-making.

The dashboard is structured into three main pages:
- Executive Overview
- Commercial Analysis
- Cohort Analysis

### 1️⃣ Executive Overview
#### 🎯 Business Context (SCQA Narrative)
***Situation***

The company operates in multiple cities, selling residential and commercial properties through different sales channels and customer segments.
Complication

Revenue fluctuates over time, and management lacks clear visibility into growth trends, performance drivers, and geographic contribution.
Question

What is the overall performance of the business, and is it growing sustainably over time?

Answer (Dashboard Insights)

The overview page presents key KPIs and time trends to evaluate financial performance and year-over-year growth.

📊 Key Metrics Included
Total Revenue (SUM of sale price)
Number of Sales
Average Ticket
Total Commission
Year-over-Year Growth (YoY %)
Year-to-Date Revenue (YTD)
Revenue by City
Revenue Trend Over Time
These metrics provide a high-level executive view of business performance.

2️⃣ Commercial Analysis
🎯 Business Objective
Identify which products, channels, and customer segments generate the highest revenue and profitability.

📊 Visualizations Included
🔹 Revenue by Property Type
Analyzes performance between residential and commercial properties.
🔹 Revenue by Sales Channel
Evaluates channel effectiveness (e.g., Broker vs Direct).
🔹 Revenue by Customer Segment
Compares revenue contribution from:
First-time buyers
Investors
High-net-worth clients
🔹 Performance Table with Conditional Formatting
Includes:
Property Type
Total Revenue
Number of Sales
Average Ticket
Conditional formatting (traffic-light logic) highlights top-performing categories.
🔹 Revenue Share (%) Tooltips
Measures created using modified filter context (CALCULATE in DAX) to display:
Revenue Share by Property Type
Revenue Share by Sales Channel
Revenue Share by Customer Segment

3️⃣ Cohort Analysis
🎯 Business Objective
Analyze customer recurrence behavior and measure retention over time.

🧮 Calculated Columns (Fact Table)
The following calculated columns were created in the fact_sales_properties table:
First Purchase Date per Customer
Cohort Month (Acquisition Month)
Sales Month (Transaction Month)

📊 Cohort Matrix Structure
Rows: Cohort Month
Columns: Sales Month
Values: Number of Sales or Total Revenue
This visualization enables:
Identification of repeat purchase patterns
Comparison of cohort performance over time
Evaluation of customer lifetime behavior

🛠️ Technical Implementation
Data Model
Star schema design
Fact table: Sales transactions
Dimension tables: Date, Property, Customer, Channel, Location
DAX Measures Created
Base Measures
Total Revenue
Number of Sales
Average Ticket
Total Commission
Filter Context Measures
Revenue Share by Category
Revenue Share by Channel
Revenue Share by Segment
Time Intelligence Measures
Year-to-Date (YTD)
Previous Year Revenue
Year-over-Year Growth (YoY %)

📈 Key Insights Generated
Residential properties generate the highest revenue contribution.
Broker channel drives the majority of sales.
First-time buyers represent the largest customer segment.
Revenue shows positive year-over-year growth.
Certain cohorts demonstrate stronger repeat purchasing behavior.

🚀 Skills Demonstrated
Data modeling (Star Schema)
Advanced DAX calculations
Time intelligence implementation
Cohort analysis
Executive storytelling using SCQA
KPI design and dashboard structuring
Business insight generation

📂 Tools Used
Power BI
DAX
Data modeling best practices

📬 Author
Ricardo Hernández
Mechatronic Engineer | NVH Specialist | Aspiring Data Analyst

If you found this project interesting, feel free to connect or reach out!
