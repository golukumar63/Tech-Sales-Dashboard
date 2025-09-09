# Tech-Sales-Dashboard

1. Project Title
Tech Sales Dashboard (2020–22)

2. Short Description / Purpose
A Power BI dashboard designed to monitor "sales, costs, and performance trends" across technology product categories and brands. It highlights KPIs, category-level sales, and brand contributions, giving management insights for performance evaluation and strategy.

3. Tech Stack
Power BI Desktop (visualizations & reporting)
Power Query (M Language) (ETL: data cleaning & transformation)
DAX (for calculated measures)
CSV/Excel / Database (data source)
Git & Git LFS (versioning the `.pbix` file)

4. Data Source
Origin: Tech sales dataset covering 2020–2022.  
Grain: Transactional sales by Category × Brand × Supervisor × Year.  
Schema:  
FactSales: Transaction records (`Total Sales`, `Cost`, `Quantity`, `Transactions`)  
DimCategory: Product categories (Monitor, CPU, SSD, etc.)  
DimBrand: Brand details (Intel, Samsung, Dell, Nvidia, etc.)  
DimSupervisor: Sales supervisor information  
DimDate: Calendar (Year, Quarter, Month)  

5. Features / Highlights

a) Business Problem
Management required a consolidated tool to evaluate "sales performance across categories and brands" while also tracking supervisors’ sales achievements. Without a dashboard, it was difficult to assess trends and performance gaps.

b) Goal of the Dashboard
Track key metrics: "Total Sales, Total Cost, Total Quantity, Transactions" 
Compare performance across "categories, brands, and supervisors" 
Identify best-performing categories and brands  
Provide insights into min, max, and average sales values  

c) Walk-Through of Key Visuals
KPI Cards:  
19M Total Sales
14M Total Cost  
2362 Total Quantity  
967 Transactions  
Min Sales: 455, Max Sales: 19K, Avg Sales: 7.92K  
Category Bar Chart: Monitors lead with 344 sales, followed by CPUs (258), Mouse (254), SSD (235).  
Brand Pie Chart: Intel, Samsung, Dell, Nvidia, Western Digital, Acer contribute to sales distribution.  
Supervisor Panel: Sales breakdown by individual supervisors for accountability and performance.  

d) Business Impact & Insights
Monitors and CPUs are top-selling categories, helping prioritize inventory and marketing.  
Intel & Samsung emerge as strong brands driving revenue growth.  
- Supervisors’ performance can be tracked transparently, aiding HR in recognizing top performers.  
- Clear visibility into cost vs. sales ensures better profit margin analysis.  


# Tech Sales Snapshort 
[![Tech Sales Dashboard](assets/tech_sales_snapshot.png)](https://github.com/golukumar63/Tech-Sales-Dashboard/blob/main/Tech%20Sales%20Snapshort.png)
