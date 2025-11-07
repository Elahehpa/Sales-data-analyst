# Adidas Sales Data Analysis using PySpark & Databricks

## Objective
This project performs an end-to-end analysis of the Adidas Sales Data (2020–2021) to uncover key business insights for optimizing sales performance and guiding data-driven strategies. Using PySpark on Databricks, it efficiently processes large datasets and delivers actionable insights through interactive analytics and visualization.

## Tools & Technologies
- Databricks Free Edition (PySpark)  
- Spark SQL for data cleaning, aggregation, and transformation  
- Power BI / Databricks Visualizations for dashboards and insights  
- Python (PySpark API) for advanced analysis and feature engineering  

## Business Metrics & KPIs

| KPI | Description |
| --- | ----------- |
| Total Sales, Profit, Avg. Price/Unit, Total Units Sold | Evaluate overall performance |
| Monthly Sales Trend | Identify peak and low seasons across 2020–2021 |
| Sales by State & Region | Analyze regional performance and growth opportunities |
| Sales by Product & Retailer | Measure profitability and product demand |
| Units Sold by Product Category | Detect top-selling categories |
| Top Performing Cities by Profit | Identify high-value markets |

## Analytical Approach
1. **Data Ingestion**  
   - Loaded the Adidas sales dataset (CSV) into Databricks Volume.  
   - Defined schema and cleaned data (handled commas, spaces, and string-to-numeric conversion).  

2. **Data Cleaning & Transformation**  
   - Replaced malformed numeric values using `regexp_replace` and `cast` in PySpark.  
   - Converted date columns to proper `DATE` type for time-series analysis.  

3. **Exploratory Data Analysis (EDA)**  
   - Used Spark SQL to calculate metrics (sales, profit, units, averages).  
   - Aggregated by month, state, region, and product category.  

4. **Visualization & Insights**  
   - Built Databricks visual dashboards showing monthly sales trends, profit by region, and product performance.  
   - Identified top retailers and cities contributing most to revenue and profit.  

## Key Insights
<img width="431" height="210" alt="image" src="https://github.com/user-attachments/assets/26f5ad16-981f-4287-b1bb-c27061f28628" />
<img width="427" height="155" alt="image" src="https://github.com/user-attachments/assets/97238e21-f11d-4115-8f1d-23cd01b17c8a" />

- Highest revenue months: November–December (holiday season).  
- Top-performing regions: California and Texas contributed 35% of total profit.  
- Most profitable product category: Footwear dominated with the highest margin.  
- Retailers driving revenue: West Gear and Foot Locker were leading in total sales.  

## 🚀 Business Impact
This analysis helps Adidas:  
- Optimize inventory planning based on regional demand trends.  
- Target marketing campaigns around peak sales months.  
- Strengthen retailer partnerships that drive higher profitability.

## View Dashboard
You can view the exported Adidas Sales Dashboard here:  
[Sales Data Analysis Dashboard.html]


