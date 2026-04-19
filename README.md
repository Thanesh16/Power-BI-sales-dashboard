# 📊 Sales Performance & Profit Analysis Dashboard

### 🔹 Description
This project focuses on analyzing sales performance, customer behavior, and profitability using an interactive dashboard built in Power BI. 

The goal of this dashboard is to track overall sales trends, evaluate product profitability by analyzing total sales against variable costs, monitor customer retention, and provide actionable insights across different regions, segments, and teams.

### 🔹 Tools & Technologies

| Tool / Concept | Application |
| :--- | :--- |
| **Microsoft Power BI** | Primary tool for data visualization and dashboard creation. |
| **DAX (Data Analysis Expressions)** | Utilized for custom measures, Time Intelligence, cumulative totals, and percentage calculations. |
| **Data Modeling** | Structuring robust relationships between data tables for accurate reporting. |

### 🔹 Key Features

| Feature | Description |
| :--- | :--- |
| **🔍 Drill-Through Navigation** | Deep dive from high-level charts directly into specific **Order Details** and **Profit Analysis** tables. |
| **👥 Customer Retention Tracking** | Dedicated metrics for monitoring Repeat Customers and Repeat Customer Percentage over time. |
| **📈 Trend & Growth Analysis** | Visualizes cumulative sales/profit and tracks Sales Growth % month-over-month. |
| **🎛️ Dynamic Slicers & Filtering** | Synced slicers across pages for Region, Segment, Team, and Date variables. |
| **💰 Profitability Segmentation** | Classifies products into categories like "High Revenue - Low Profit" based on cost data. |

### 🔹 Core KPIs

| Metric | Value | Metric | Value |
| :--- | :--- | :--- | :--- |
| **Total Sales** | 227K | **Total Orders** | 46 |
| **Total Profit** | 68.02K | **Total Customers** | 500 |
| **Profit Margin** | 30.00% | **Repeat Customers** | 43 (8.60%) |
| **Total Quantity Sold** | 229 | **Avg RPC** | 5.27K |

### 🔹 Key Insights

| Category | Finding |
| :--- | :--- |
| **Product Performance** | Tablets are the most sold product (38 units), while Printers are the least sold (6 units). |
| **Revenue vs. Profit** | Smartphones generate the highest total sales volume but are flagged as "High Revenue - Low Profit" due to high variable costs (~30.6K cost vs 43.7K sales). |
| **Top Customers** | Customer 181 generates the highest overall sales volume; Customer 118 purchased the highest quantity of products (17 units). |
| **Category Dominance** | The Electronics category drives the majority of sales (61.49%) compared to Accessories (38.5%). |
| **Sales Trends** | While cumulative sales show steady growth, month-over-month Sales Growth % highlights periods of negative growth (dipping to -40.43% in the latest period) requiring strategic attention. |

### 🔹 Screenshots

| Page / View | Image Path |
| :--- | :--- |
| **Sales Overview** | `![Sales Overview](./Screenshots/Sales_Overview.png)` |
| **Sales Trend** | `![Sales Trend](./Screenshots/Sales_Trend.png)` |
| **Top Performance** | `![Top Performance](./Screenshots/Top_Performance.png)` |
| **Segment Analysis** | `![Segment Analysis](./Screenshots/Segment_Analysis.png)` |
| **Profit & Revenue Analysis**| `![Profit & Revenue Analysis](./Screenshots/Profit_and_Revenue_Analysis.png)` |
| **Profitability Analysis** | `![Profitability Analysis](./Screenshots/Profitability_Analysis.png)` |

*(Note: Ensure the image file names in your `Screenshots` folder match the paths above.)*

### 🔹 Project Structure

```text
Power-BI-sales-dashboard/
│
├── Backup/
├── Development/
├── Published/
├── Raw data/
├── Screenshots/
├── Theme/
└── README.md
