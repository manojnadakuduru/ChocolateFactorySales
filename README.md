# Chocolate Factory Sales

### 1.	Project Title
🍫 Chocolate Analytics: Chocolate Factory Sales Insights Dashboard
An interactive Power BI dashboard designed to analyze end-to-end chocolate sales performance, focusing on revenue, profitability, shipment patterns, product performance, geographic distribution, and salesperson contribution.

### 2.	Short Description
The Chocolate Factory Sales Dashboard provides a consolidated view of sales and profit performance across products, regions, and sales teams. It enables stakeholders to track key KPIs, compare year-over-year trends, and identify high-performing products and geographies to support data-driven business decisions.


### 3.	Tech Stack
The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Primary platform for building interactive visuals and dashboards

• 📂 Power Query – Data cleaning, transformation, and preparation

• 🧠 DAX (Data Analysis Expressions) – Used for KPI calculations, YoY comparisons, and profit metrics

• 🧱 Data Modeling – Fact and dimension tables structured to enable cross-filtering and drill-downs

• 📁 File Format – .pbix for development and .png for dashboard previews

### 4.	Data Source & Data Model
Source: Simulated chocolate factory sales dataset
The data represents end-to-end chocolate sales operations, including shipment-level transactions, product attributes, geographic regions, salesperson information, and a dedicated calendar table for time intelligence analysis.
The dataset is structured to support analytical reporting, KPI tracking, and year-over-year comparisons.

**Data Model Design**
The dashboard follows a star schema design, with a central fact table and multiple dimension tables to enable efficient filtering, aggregation, and scalability.

**• Fact Table – shipments**
Contains transaction-level data including:
1)Sales amount and cost
2)Boxes shipped (including binned distributions)
3)Order status and shipment date
4)Foreign keys linking to product, location, salesperson, and calendar dimensions

**• Dimension Tables**
1)products – Product details such as product name, category, and cost per box
2)locations – Geographic attributes including region and country
3)people – Salesperson details including name and profile image
4)calendar – Date attributes (month, weekday, start of month) enabling time-based analysis
5)This design supports flexible slicing by product, region, salesperson, and time.
![Dashboard Preview](https://github.com/manojnadakuduru/ChocolateFactorySales/blob/main/DataModel.png)


### 5.	Features / Highlights
Business Problem
Sales and operations teams require a unified view of performance across products, regions, and sales representatives. Without a centralized analytical model, answering questions such as sales growth, profit contribution, shipment behavior, and salesperson effectiveness becomes time-consuming and error-prone.

**Goal of the Dashboard**
To deliver a business-ready analytics solution that:
1)Tracks revenue, shipments, and profitability at scale
2)Enables year-over-year and time-based performance comparisons
3)Identifies top-performing products, regions, and salespeople
4)Provides operational insight into shipment distribution patterns

**Walkthrough of Key Visuals**

• Executive KPIs (Top Banner)
Total Amount, Total Boxes, Shipment Count, Total Profit, and Profit % provide an instant health check of business performance.

• YoY Trend Analysis (Line Charts)
Compares current year vs prior year for both sales amount and shipment volume, helping identify seasonality and growth trends.

• Shipment Distribution (Histogram)
Displays how shipments are distributed across box-volume ranges, supporting logistics and operational analysis.

• Top Products (Treemap)
Highlights top 5 revenue-generating products for quick product performance assessment.

• Product Performance Table
Shows product-level revenue and profit percentage, allowing margin-based decision-making.

• Salesperson Performance Table
Ranks sales representatives by revenue, boxes shipped, and profit %, supporting performance reviews and incentive planning.

• Geographic Sales Breakdown (Donut Chart)
Visualizes regional and country-level sales contribution to identify strong and underperforming markets.

• Date Slicer (Calendar Table)
Enables dynamic filtering across months and years using a dedicated calendar dimension.

**Business Impact & Insights**
• Revenue & Profit Visibility
Leadership gains instant insight into revenue growth, profit margins, and shipment trends.
• Product Optimization
Helps distinguish high-margin vs high-volume products for better pricing and assortment decisions.
• Sales Performance Management
Enables fair and data-driven evaluation of salesperson contributions.
• Operational Efficiency
Shipment distribution analysis supports logistics planning and workload balancing.
• Scalable BI Architecture
Star schema design ensures the model is extensible for future data sources and advanced analytics.

### 6.	Screenshot
![Dashboard Preview](https://github.com/manojnadakuduru/ChocolateFactorySales/blob/main/Chocolate_Factory_Sales.png)
