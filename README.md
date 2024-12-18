# LITA_Data_Analysis_Project

### Project Title: Retail_Store_Sales_Performance_Analysis
---

Table Outline.
---
[Project Overview](#project-overview)

[Objective](#objective)

[Data Source](#data-source)

[Tools Used](#tools-used)

[Dataset](#dataset)

[Basic Statistics About This Dataset](#basic-statistics-about-this-dataset)

[Key Features](#key-features)

[Screenshots of Excel Dashboard](#screenshots-of-excel-dashboard)

[Overall Summary](#overall-summary)

[Screenshots of SQL Queries](#screenshots-of-sql-queries)

[Power BI Dashboard Overview](#power-bi-dashboard-overview)

[Summary](#summary)



### Project Overview.
---

This project focuses on Analyzing the sales performance of a retail store. It is to uncover key insights, identify trends and provide actionable insights to guide better decision-making and craft data-driven stories. Using statistical method and data visualization to explore what influence regional performance, top-selling or performing products and monthly sales trends.

### Objective.
---

- To analyse Sales trends to make informed decisions such as to know high and low performing periods.
- To identify top-performing products and regions contributing to the largest revenue.
- To understand potential customer segments to develop effective future sales strategies.

### Data Source
---
The dataset for this analysis was provided by LITA the_Incubator-Hub, an initiative to empower women as 'Tech-Sis' in the technology field. The data was provided in Microsoft Excel Worksheet (.xlsx) format. It was converted to CSV before importing to SQL for simpler, cleaner, and easier to work with for direct data import into SQL database. And for creating visuals on Power BI, Get Data was used to import data from Excel.  

### Tools Used
---
- Microsoft Excel [Download Here](https.//www.microsoft.com)
1. Data Cleaning: Checked for inconsistent rows, and columns, duplicate values, and null rows. Ensured data quality by removing duplicate entries.
2. Data Exploration: Using pivot tables to organize, summarize, and filter the data for clear interpretation.
3. Data Transformation: Ensured all data fields were assigned the correct data types, the numerical fields formatted as accounting for ideal financial reports, expense tracking, and any data where monetary values are used, for readable presentation. Sorted the dataset by the date column to organize transaction orderly. Added a new column to calculate the total sales of each entries using Sum function: ```SUM(Quantity*UnitPrice)
4. Exporting Data: Preparing the cleaned dataset for further analysis in Structured Query Language (SQL) and visualization in Power BI

- Structured Query Language
1. Data Retrival: Writing SQL queries to extract relevant datasets for analysis, such as total sales for each product category, number of sales transactions in each region, highest-selling product, total revenue per product, monthly sales total for the current year, top five customers by total purchase amount, percentage of total sales contributed by each region, and products with no sales in the last quarter.
2. Data Query: For querying of data.
  
- Power BI (Business Intelligence)
1. Data Integration: Importing and transforming data from Excel and SQL databases, to create a unified data model for analysis.
2. Interactive Dashboard: To visualizes the insights found in Excel and SQL which includes a sales overview, top-selling products, and regional breakdowns.
3. Data Visualization: Creating various visualizations like bar chart, pie chart, card and matrix to highlight important metrics such as total sales, product performance, and regional breakdowns.
4. StoryTelling with Data: Using visual narratives to guide business owner through findings, emphasizing trends, and actionable insights that can inform business decisions.
- GitHub: For building my portfolio.

### Dataset
---

- Sales Data from Capstone by LITA_TheIncubator_Hub. It includes this key columns; 
1. OrderID: This is a unique identifier for each order.
2. CustomerID: This is the unique identifier for each customer in the dataset, allowing for tracking customer-specific purchases and behaviors.
3. Product: This is an item purchased by each customer.
4. Region: This is the geographical location where the sale occured.
5. OrderDate: This is the date of the order or sales date.
6. Quantity: It is the number of items sold.
7. UnitPrice: The price of a single product sold.
  
### Basic Statistics About This Dataset.
---
1. Total Sales: 2,101,090.
2. Total Quantity Sold: 68,461.
3. Total Unit Price: 290,260.
4. Average Sales: 212.
5. Number of Customers: 501.

### Key Features.
---
- Interactive dashboard using PivotTables.
- Visual representation of insights found in Excel and SQL.
- Visual dashboard of sales overview, top-performing products, and regional breakdown.


### Screenshots of Excel Dashboard
Total Revenue by Product, Region, and Month.
---

<img width="173" alt="Total sale by PRM" src="https://github.com/user-attachments/assets/c3be8fef-ce75-4f70-9b7a-195541616ab0">

### Overall Summary
- Observation: This pivot table reveals that shoes leads in sales with a peak in South region, and rise significantly in February which dropped drastically in West region in August, indicating a seasonal demand. Shirt followed with a little difference which did well in East and North regions in July and January respectively.
- Inferences: Shoes popularity in February sales may have benefited from Valentine's Day or a seasonal promotion that boosted demand, especially when it's suitable for gifting. While shirt high demands in the East region may be due to the seasonal weather which could have increased demand for lighter clothing, while demand in north could be as a result of milder weather in January. Regardless different regions often have unique fashion preferences or seasonal purchasing habits.
- Implications: To depends on these trends, the business owner should consider extending marketing efforts for lower-performing products such as socks, gloves, and jackets. And also look into factors affecting other regions where shoes and shirt are not performing well. Additionally, it is essential for the business owner to prepare adequately for the holiday season with increased online inventory, and hire seasonal workers. 


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



 ### Screenshots of SQL Queries
 ---
 Total Sales for Each Product Category.
 ---






 <img width="395" alt="SQL Total sale" src="https://github.com/user-attachments/assets/2ad88ac9-c988-4875-b515-f66403c3f992">



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




<img width="636" alt="Top 5 Customer sql sales" src="https://github.com/user-attachments/assets/019d3b10-93d9-469a-8b9a-b252ff77532c">



Percentage Of Total Sales Contributed By Each Region.
---




<img width="468" alt="Percentage Sql" src="https://github.com/user-attachments/assets/30758fec-0e6c-41ab-8da2-2e17dd23af56">
















Products With No Sales In The Last Quarter.
---
<img width="368" alt="SQL No Sales products" src="https://github.com/user-attachments/assets/52246083-fb93-4a4b-aeee-199245a376b3">

### Power BI Dashboard Overview.
---




<img width="435" alt="newest dashboard visualization" src="https://github.com/user-attachments/assets/0f370e0a-fb0e-4660-aaca-a31b03320b33">






### Sales Overview.
---




<img width="428" alt="Newest Sales overview" src="https://github.com/user-attachments/assets/27ce950a-c29d-402b-90a3-3f71c3063950">



- The monthly sales trends indicate inconsistent growth throughout the year, with notable peak in February. January sales aligns with festive period, as post-holiday shopping boosts demand for shirt while June gloves sales may rise due to outdoor activities like gardening and sports, as well as an increase in construction and home improvement projects. Demand in the food service sector during summer events combined with pontential discounts or promotions can also contribute to this seasonal trend.
- Shoes generating 613,380 in revenue, and Shirts contributing 485,600 in revenue showcased their dominance in product lineup. 

### Top-Performing.
---
- In this sales performance analysis, shoes and shirts emerged as the top-performing categories, driving the majority of revenue during the reporting period. Together accounting for 52.31% of sales which is more than half of the revenue. Shoes have proven particularly strong, reflecting consumer trends towards casual and athletic wear, while shirts have benefitted from increasing demand for sustainable options. Recent marketing campaigns may have effectively engaged customers, contributing to this success. Expectation for continued growth in these categories means more targeted strategies and seasonal promotions.






<img width="291" alt="Top performing newest" src="https://github.com/user-attachments/assets/96520a7c-bdf8-4177-aa67-f8e64e1b2933">



### Regional Performance.
---




<img width="205" alt="Regional breakdown newest" src="https://github.com/user-attachments/assets/adf9774c-327e-4228-a9fe-20308c30ca93">

- The regional breakdown reveals that South region leads in sales, contributing 44.16% to total revenue, driven by strong demand for casual footwear and gloves. Meanwhile, West region is lagging at 14.29% of total sales mostly due to heightened competition and economic downturns. Seasonal Trends indicate that East and North region see peaks in winter and summer, respectively suggesting targeted marketing opportunities. Overally, regions with tailored strategies have shown positive growth, while others may require re-evaluation of their market approach to capitalize on emerging trends. 


### Summary
---
- In conclusion, this analysing indicates a strong sales performance for shoes and shirts, driven by customer trends and effective marketing strategies. Regional insights reveal opportunities for growth and challanges that need addressing. By leveraging targeted promotions and understanding market dynamics, business owner can enhance sales performance and customer engagement moving forward. Continuous monitoring of sales trends and customer preferences will be essential in adapting these strategies to ensure sustained growth.




    [LITA Capstone Dataset.xlsx](https://github.com/user-attachments/files/17562108/LITA.Capstone.Dataset.xlsx)


