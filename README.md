# LITA_Data_Analysis_Project

### Project Title: Retail_Store_Sales_Performance_Analysis
---

### Project Overview

This project focuses on Analyzing the sales performance of a retail store. It is to uncover key insights, identify trends and provide actionable insights to guide better decision-making and craft data-driven stories. Using statistical method and data visualization to explore what influence regional performance, top-selling or performing products and monthly sales trends.

### Objective.
---

- To analyse Sales trends to make informed decisions such as to know high and low performing periods.
- To identify top-performing products and regions contributing to the largest revenue.
- To understand potential customer segments to develop effective future sales strategies.

### Tools Used
---

- Microsoft Excel
  1. Data Cleaning: Removing duplicates, and standardizing formats for consistency.
  2. Data Exploration: Using pivot tables to organize, summarize, and filter the data for clear interpretation.
  3. Data Transformation: Using functions and formulas to compute new fields, categorize data, and create basic aggregations.
  4. Exporting Data: Preparing the cleaned dataset for further analysis in Structured Query Language (SQL) and visualization in Power BI

- Structured Query Language
   1. Data Retrival: Writing SQL queries to extract relevant datasets for analysis, such as total sales for each product category, number of sales transactions in each region, highest-selling product, total revenue per product, monthly sales total for the current year, top five customers by total purchase amount, percentage of total sales contributed by each region, and products with no sales in the last quarter.
   2. Data Query: For querying of data.
  
- Power BI (Business Intelligence)
  1. Data Integration: Importing and transforming data from Excel and SQL databases, to create a unified data model for analysis.
  2. Interactive Dashboard: To visualizes the insights found in Excel and SQL which includes a sales overview, top-selling products, and regional breakdowns.
  3. Data Visualization: Creating various visualizations (E.g Bar charts, pie charts) to highlight important metrics such as total sales, product performance, and customer demograhics.
  4. StoryTelling with Data: Using visual narratives to guide business owner through findings, emphasizing trends, and actionable insights that can inform business decisions.
- GitHub: For building of portfolio

### Dataset
---

- Sales Data from Capstone by LITA_TheIncubator_Hub. It includes this key columns; 
  1. OrderID: This is a unique identifier for each order.
  2. CustomerID: This is the unique identifier for each customer in the dataset, allowing for tracking customer-specific purchases and behaviors
  3. Product: This is an item purchased by each customer.
  4. Region: This is the geographical location where the sale occured.
  5. OrderDate: This is the date of the order or sales date
  6. Quantity: It is the number of items sold
  7. UnitPrice: The price of a single product sold
  

### Key Features
---
- Interactive dashboard using PivotTables.
- Visual representation of insights found in Excel and SQL
- Visual dashboard of sales overview, top-performing products, and regional breakdown


### Screenshots of Excel Dashboard
Total Revenue by Product, Region, and Month.
---

<img width="173" alt="Total sale by PRM" src="https://github.com/user-attachments/assets/c3be8fef-ce75-4f70-9b7a-195541616ab0">

### Overall Summary
- Observation: This pivot table reveals that shoes leads in sales with a peak in South region, and rise significantly in February which dropped drastically in West region in August, indicating a seasonal demand. Shirt followed with a little difference which did well in East and North regions in July and January respectively.
- Inferences: Shoes popularity in February sales may have benefited from Valentine's Day or a seasonal promotion that boosted demand, especially when it's suitable for gifting. While shirt high demands in the East region may be due to the seasonal weather which could have increased demand for lighter clothing, and demand in north could be as a result of milder weather in January. Regardless different regions often have unique fashion preferences or seasonal purchasing habits.
- Implications: To depends on these trends, the business owner should consider extending marketing efforts for lower-performing products such as socks, gloves, and jackets. And also focus more on other regions that shoes and shirt are not performing well. Additionally, it is essential for the business owner to prepare adequately for the holiday season with increased online inventory, and hire seasonal workers. 


Average Sales Per Product and Total Revenue by Region.
---

<img width="334" alt="Excel average per product and total revenue by regions" src="https://github.com/user-attachments/assets/6d7ff9f4-c1e4-46f2-b322-df302e141989">


- Observations: Shoes and shirts have the highest average sales, while socks, jackets, hats, and gloves have significantly lower average. And also, South and East regions generate the highest revenue, while North and West regions contribute less to the total.

- Inferences: This may indicate that shoes and shirts are more popular in some regions, possibly due to better marketing, customer preferences or alignment with current trends. Lower averages sales for socks, hats, gloves, and jackets might suggest they are less appealing to customers. And also, the South and East might have a larger customer base, higher spending power or be more interested in current products. Lower revenue in the North and West could be due to lower brand awareness, or regional preferences that aren't aligned with the products offered.

- Implications: The business owner should consider focusing marketing efforts on gloves, hats, jackets, and socks to maximize revenue. Maybe targeted marketing, or product improvements boost their sales and increase average sales. Also, for the regions, focus expansion and marketing efforts in the South and East to maintain growth, and in the North and West, business owner should consider adjusting the product lineup to suit local preferences better, increase brand awareness and running region-specific promotions to drive revenue.


Percentage of Each Product by Total Revenue.
---


<img width="308" alt="Excel Percentage new" src="https://github.com/user-attachments/assets/c1e40eb1-590b-4565-91b0-a61033440ec8">

- Observations: 
 1. Shoes accounted for 29% of total sales, demonstrating strong demand and popularity among customers. 
 2. Shirts followed closely, contributing 23% to overall sales figures.
 3. South region emerged as the top-performing market, representing 44% of total sales though not across all products, with the East region also showing significant sales at 23%.

- Inferences:
  1. The high sales figures for shoes suggest effective marketing strategies targeted towards the customers base in the south region.
  2. The regional performance indicates potential geographic advantages, such as local promotional efforts.

-  Implications:
    1. The business owners may consider focusing their marketing efforts on regions where sales are strong to capitalize on existing demand.
    2. There is also an opportunity for increasing sales in low-performing regions by analyzing the strategies employed in successful markets.

### Recommendations for Future Strategy.
- Explore the factors contributing to the success of shoes and shirts in the South, North, and East regions to replicate these strategies in other markets.
- Conduct further research to understand customer preferences in regions and products with lower sales to identify barriers to growth.

 ### Final Thoughts
 In conclusion, understanding the dynamics of the highest-selling products, and top-performing regions can provide, valuable insights for future business strategies. By leveraging this data, business owners can enhance their sales approaches and optimize their product offerings to maximize revenue. 
    

 ### Screenshots of SQL Queries
 ---
 Total Sales for Each Product Category.
 ---
 

 

<img width="395" alt="SQL Total sale" src="https://github.com/user-attachments/assets/425f1550-5104-45d6-9de7-8585c9e0161d">


Number of Sales Transactions in Each Region
---




<img width="421" alt="SQL 2nd query sales" src="https://github.com/user-attachments/assets/db3d88a3-3db4-41c5-b812-f92b7c2b66bc">

Highest-Selling Product by Total Sales Value




<img width="419" alt="SQL Highest-Selling product" src="https://github.com/user-attachments/assets/655dc42b-ac85-45a1-9e3d-31640836f7a5">

Total Revenue Per Product.
---





<img width="455" alt="Total Revenue per product" src="https://github.com/user-attachments/assets/69777853-eb49-4de4-a141-cda2ab031f86">

Monthly Sales Totals For The Current Year.
---



<img width="432" alt="Total sales current year" src="https://github.com/user-attachments/assets/995bdddf-92a9-4b27-8d0b-47b9463a5875">

Top 5 Customers By Total Purchase Amount.
---





<img width="430" alt="Top 5 products SQL" src="https://github.com/user-attachments/assets/01225903-cb31-401f-9f75-bba09b961891">

Percentage Of Total Sales Contributed By Each Region.
---




<img width="468" alt="Percentage Sql" src="https://github.com/user-attachments/assets/30758fec-0e6c-41ab-8da2-2e17dd23af56">
















Products With No Sales In The Last Quarter.
---
<img width="368" alt="SQL No Sales products" src="https://github.com/user-attachments/assets/52246083-fb93-4a4b-aeee-199245a376b3">

### Power BI Dashboard Overview.
---




<img width="485" alt="Dashboard Sales Overview" src="https://github.com/user-attachments/assets/346c9092-da3b-4c13-bb8d-802c8c6ea1fd">




### Sales Overview.
---






<img width="440" alt="new sales trends visuals" src="https://github.com/user-attachments/assets/ceaec07f-eed1-4cc9-bafa-c9c70c339dd6">

### Top-Performing.
---




<img width="468" alt="Top 5 customer dashboard" src="https://github.com/user-attachments/assets/318a41fb-cc20-4421-81d2-023657c604b3">

### Regional Performance.
---





<img width="418" alt="Regional Visuals pbi" src="https://github.com/user-attachments/assets/3ea503d0-a9ab-476f-9d4a-7515f7b9bc99">



### Recommendations for Future Strategy.
- Explore the factors contributing to the success of shoes and shirts in the South, North, and East regions to replicate these strategies in other markets.
- Conduct further research to understand customer preferences in regions and products with lower sales to identify barriers to growth.

 ### Final Thoughts
 In conclusion, understanding the dynamics of the highest-selling products, and top-performing regions can provide, valuable insights for future business strategies. By leveraging this data, business owners can enhance their sales approaches and optimize their product offerings to maximize revenue. 
    

