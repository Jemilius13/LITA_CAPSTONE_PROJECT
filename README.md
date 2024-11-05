# LITA_CAPSTONE_PROJECT
------------------------------------------------
Introduction to the Capstone Project on Data Analysis. 
The Capstone Project is a comprehensive data analysis initiative that uses datasets to extract meaningful insights and drive informed decision-making. This project integrates various data analysis tools and techniques, specifically Excel, SQL, and Power BI, to showcase a holistic data management and visualization approach.

Throughout the project, we will work with diverse datasets that require cleaning, manipulation, and analysis to uncover trends and patterns. Utilizing Excel, we will perform initial data exploration and analysis, applying functions and pivot tables to summarize key findings. 
Next, SQL will be employed for more advanced data querying and management, allowing us to retrieve and manipulate large datasets from relational databases efficiently.

Finally, we will harness the power of Power BI to create interactive visualizations and dashboards that present our findings in a user-friendly format. This will enable stakeholders to engage with the data dynamically, facilitating a deeper understanding of the insights derived from the analysis.
Overall, this Capstone Project aims to enhance our data analysis skills and demonstrate our ability to effectively utilize analytical tools to solve real-world problems, ultimately contributing to data-driven decision-making processes.

### Project title: "A Comprehensive Data Analysis Approach: Excel, SQL, and Power BI Integration"


[CAPSTONE PROJECT OVERVIEW](#capstone-project-overview)

[PROJECT OVERVIEW](#project-objectives)

[EXPECTED OUTCOMES](#expected-outcomes)

[PROJECT 1 SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE USING EXCEL](#project-1-sales-performance-analysis-for-a-retail-store-using-excel)

[DATA SOURCES](#data-sources)

[METRICS OF FOCUS](#metrics-of-focus)

[TOOLS USED](#tools-used)

[DATA VISUALIZATION](#data-visualization)

[OTHER INTERESTING REPORTS](#other-interesting-reports)

[PROJECT 1B SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE USING SQL](#project-1b-sales-performance-analysis-for-a-retail-store-using-sql)

[TOOLS USED](#tools-used)

[EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

[QUERIES AND OUTPUT](#queries-and-output)

[PROJECT 1C SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE USING POWERBI](#project-1c-sales-performance-analysis-for-a-retail-store-using-powerbi)

[TOOLS USED](#tools-used)

[DASHBOARD OVERVIEW](#dashboard-overview)


[CONCLUSION](#conclusion)





### CAPSTONE PROJECT OVERVIEW: 
-----------------------------
The Capstone Project is a comprehensive data analysis initiative designed to apply advanced analytical techniques using Excel, SQL, and Power BI. This project aims to harness data from multiple datasets to uncover insights, identify trends, and drive informed decision-making.

### PROJECT OBJECTIVES:
-----------------------------------
  - Data Collection and Preparation: Gather various datasets relevant to the project's theme, ensuring they are clean, organized, and ready for analysis.
  - Data Analysis Using Excel: Utilize Excel's powerful functions and features, such as pivot tables, formulas, and charts, to conduct exploratory data analysis and derive preliminary insights.
  - Database Management with SQL: Employ SQL to manipulate and query data from relational databases. This includes filtering, aggregating, and joining datasets to prepare for deeper analysis.
  - Data Visualization with Power BI: Create interactive dashboards and visual reports in Power BI, showcasing the findings from the analysis. This allows stakeholders to easily interpret data trends and patterns.

### EXPECTED OUTCOMES:
----------------------------------
A comprehensive report detailing the methodologies used, findings, and recommendations based on the analysis.
Interactive visualizations that present the data in an engaging format, facilitating better understanding and decision-making.
Enhanced skills in data manipulation, analysis, and visualization using industry-standard tools.

This capstone project reinforces analytical skills and provides practical experience handling real-world data scenarios, preparing participants for future roles in data analysis and business intelligence.

### PROJECT 1: SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE USING EXCEL
-------------------
In this project, I am tasked with analyzing the sales performance of a retail store. I'll  need to explore sales data to uncover key insights such as top-selling products, regional performance, and monthly sales trends. 

  -  Excel:
     1.  Perform an initial exploration of the sales data. Use pivot tables to summarize total sales by product, region, and month.
     2.   Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.
     3.   Create any other interesting report.

### DATA SOURCES
--------------
The Data sources include the following key points:
   1. ORDER_ID: A unique identifier assigned to each order in a system.
   2. CUSTOMER_ID: A unique identifier for each customer, linking them to specific orders and other relevant customer details.
   3. PRODUCT: The item being purchased in the order, usually described by a name, code, or category.
   4. REGION: The geographical area where the order is placed or delivered.
   5. ORDER DATE: The date the order was placed, providing insight into the timing and frequency of orders.
   6. QUANTITY: The number of units of the product being ordered.
   7. UNIT PRICE: The price of a single product unit, which can help calculate the total cost when multiplied by quantity.
      
These datasets collectively provide a comprehensive view of sales performance, customer behavior, and market dynamics, enabling informed decision-making.

### METRICS OF FOCUS
------------------
 Total Sales By Product: The total revenue generated from each product is calculated by summing up the sales of each product across all orders. This helps identify the best-selling and most profitable products.
 - Total Sales By Region: The total revenue generated within each geographic region, is useful for understanding regional demand and performance.
 - Total Sales By Month: The monthly revenue generated provides insights into seasonal trends and monthly sales performance.
 - Average Sales per Product: The average revenue generated by each product, is calculated by dividing the total sales of each product by the number of sales instances. This helps assess the average contribution of each product to 
     revenue.
  Total Revenue by Region: The overall revenue generated within each region is found by summing all sales in that region. This metric is valuable for understanding which regions contribute the most to total revenue.

### TOOLS USED
-------------------------
 - Microsoft Excel: 
    - Pivot Tables: Summarizing data and generating insights based on revenue, units sold, and transaction categories.
    - Formulas and Functions: Calculate performance metrics and automate processes like sorting and filtering.
    - Data Visualizations (Charts, Graphs): To create visual representations of trends, comparisons, and key insights. 

### DATA VISUALIZATION
----------------------------------
 1. ### TOTAL SALES BY PRODUCT

## PIVOT TABLE:
--------------------
![TOTAL SALES BY PRODUCT, PIVOT TABLE](https://github.com/user-attachments/assets/9f24fae7-9be9-49bf-b75b-93f15478bd23)



#### PIVOT CHART FOR TOTAL SALES BY-PRODUCT:
------------------------

![TOTAL SALES BY PRODUCT, GRAPH](https://github.com/user-attachments/assets/673dedaa-1618-4bd7-98fc-9a91e6b8e60b)


![TOTAL SALES BY PRODUCT, GRAPHLINE](https://github.com/user-attachments/assets/b302f5a3-eb34-423d-b4b6-c370f60e5b90)


DEDUCTIONS:
-------------------------------------------

  1.  General Total Sales Trajectory: The chart shows a positive upward trend in total sales across different products, indicating that sales are relatively high for certain products and lower for others.
  2.  Product Performance:
       - Shoes have the highest sales, reaching over 600,000 units, making them the most popular product in this dataset.
       - Shirts also perform well, with nearly 500,000 units sold.
       - Hats and Gloves have moderate sales, in the range of 300,000 units.
       - Jackets and Socks have the lowest sales figures, with Jackets slightly outperforming Socks.
  3.   Overall Product Allocation Strategy:
The current allocation suggests prioritizing resources towards high-performing products (Shoes and Shirts) while developing targeted strategies to improve the sales of lower-performing ones (Jackets and Socks).

### CONCLUSION
-------------------------
To maximize revenue, the company should maintain high stock levels and promotional efforts for top-selling items (Shoes and Shirts). For lower-performing products like Jackets and Socks, targeted strategies, such as seasonal promotions or bundling with popular items, may help boost sales. The overall sales trajectory suggests a well-balanced product mix, but improvements in marketing and inventory for underperforming items could enhance total sales performance.


 2. ### TOTAL SALES BY REGION
    -----------------------------------
 PIVOT TABLE:
----------

![TOTAL SALES BY REGION, PIVOT TABLE](https://github.com/user-attachments/assets/1a0bc07d-a316-4b96-bdcd-71105faf840a)


#### PIVOT CHART FOR TOTAL SALES BY REGION:
-----------------------------------

![TOTAL SALES BY REGION,PIECHART](https://github.com/user-attachments/assets/0b1ec372-b8c4-4fa3-b000-d2f81f99cd40)

![TOTAL SALES BY REGION, LINECHART](https://github.com/user-attachments/assets/50468c01-f97d-4588-a42a-474fd7c3d6ff)


DEDUCTIONS: 
--------------
  1. General Total Sales by Region Trajectory: The sales trend across regions sharply increased from West to South. Sales in the South region are significantly higher (927,820)     
     compared to the other regions, this region has the highest demand or market penetration.
  2. Product Performance on Total Sales by Region:
     The South region's dominance suggests it might have the highest demand across all product lines, making it a priority for inventory and marketing investments.
     The North and West regions, having smaller portions of the total sales, could represent growth opportunities. Expanding marketing strategies or conducting market research in 
     these regions might reveal untapped potential.
     While not as high as the South, the East region shows steady performance, suggesting it might also benefit from targeted promotions to increase its share further.
  4. Overall Region Allocation Strategy: The current region allocation indicates that the South is the dominant market, and strategies to maintain or further strengthen its share are essential. The East and North regions present moderate performance but show potential for improvement through focused marketing. The West region is the weakest, suggesting the need      for an in-depth evaluation to identify growth opportunities or to consider alternative strategies tailored to this region's market dynamics.

#### CONCLUSION
----------------------------
The South region is the clear leader in sales, making it a critical area for maintaining high inventory and a strong marketing focus. The West region’s lower performance suggests a need for strategic improvements in market penetration or customer outreach. The East and North regions perform moderately, with potential for growth through targeted campaigns. Overall, focusing on the South while developing tailored strategies for the other region could help optimize total sales across all markets.



### TOTAL SALES BY MONTHS
-------------------
 PIVOT TABLE:
 ----------------

![total sales by month, redo](https://github.com/user-attachments/assets/458fae2a-368c-4bd6-836e-2a3888be8def)


#### PIVOT CHART FOR TOTAL SALES BY MONTH:
------------------------------------------------

![TOTAL SALES BY MONTH, GRAPH](https://github.com/user-attachments/assets/3e168820-b66d-4725-b30c-23548da528c1)


![TOTAL SALES BY MONTH, GRAPHLINE](https://github.com/user-attachments/assets/fd053dc7-a019-4a27-8c95-b60b6199f6dc)

DEDUCTIONS:
------------------------
  1. General Total Sales by Month Trajectory: The sales trajectory shows significant fluctuations throughout the year, with a peak in February and a general decline afterward. There’s          another small increase around June and July, followed by a gradual decline in the later months. The lowest points occur in April and November-December.
  2.  Product Performance on Total Sales by Month:
     The peak in February could indicate a seasonal promotion, holiday, or sales event that drives higher demand.
     The mid-year rise around June-July might be due to mid-year sales, summer demand, or other market activities.
     The sharp drops in April and the end of the year may indicate a need for targeted strategies in these months, such as promotional events or discounts to increase sales.
  3. Overall Monthly Allocation Strategy: The monthly allocation strategy aims to optimize resources by aligning inventory, staffing, and marketing with sales patterns. During high-sales 
      months (February and mid-year), resources are maximized with increased inventory, staffing, and targeted marketing. In contrast, low-sales months (April, and November-December) 
      focus on  cost efficiency through reduced inventory levels, discounts, and demand-stimulating promotions. Moderate sales months maintain balanced stock and steady promotional       
      efforts to support sustainable growth. This approach enhances cost management, customer satisfaction, and sustained growth throughout the year by strategically leveraging peak sales 
       periods.

#### CONCLUSION
-----------------------
The sales analysis identifies Shoes and Shirts as the top-performing products, with the South region leading in sales and notable seasonal peaks in February and mid-year. Fluctuations in sales highlight the need for targeted promotional strategies during low-sales months and resource optimization during peak periods. Implementing a well-aligned monthly allocation strategy will enhance inventory management, staffing, and marketing efforts, ultimately fostering sustainable growth and improving customer satisfaction throughout the year.


#### Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.
------------------
   #### Average total sales for each product using Excel Functions
                =AVERAGEIF(C:C,"Shirt",H:H)
                =AVERAGEIF(C:C,"Shoes",H:H)
                =AVERAGEIF(C:C,"Hats",H:H)
                =AVERAGEIF(C:C,"Gloves",H:H)
                =AVERAGEIF(C:C,"Jacket",H:H)
                =AVERAGEIF(C:C,"Socks",H:H)

![Average total sales for each product](https://github.com/user-attachments/assets/e1889fa6-5ac1-4272-8a41-10133a1adcae)

![Average total sales,pivot](https://github.com/user-attachments/assets/4116ecd5-b3ac-428a-a247-5baf717200a7)


  #### Total Revenue by Region using Excel Functions
                =SUMIF(D:D,"South",H:H)
                =SUMIF(D:D,"North",H:H)
                =SUMIF(D:D,"West",H:H)
                =SUMIF(D:D,"East",H:H)

![TOTAL REVENUE BY REGION](https://github.com/user-attachments/assets/631070a0-96b5-4d04-bd77-1116fcad3fda)


![TOTAL SALES BY REGION, PIVOT TABLE](https://github.com/user-attachments/assets/408c6946-4822-498e-a7aa-b44c7e007db1)

####  OTHER INTERESTING REPORTS
--------------

![top 5 products](https://github.com/user-attachments/assets/61ae587d-4725-4a54-bd18-5e4d7c2dedf4)


### TOTAL SALES BY MONTH/YEAR IN 2023
--------------
 PIVOT TABLE
 ---------
 
![TOTAL SALES BY Y2023](https://github.com/user-attachments/assets/1df5e6a7-ecb2-4c0a-9977-aa5a6fc63edd)



#### FILTERED CHART FOR THE YEAR 2023
-----------------

![TOTAL SALES BY Y2023](https://github.com/user-attachments/assets/672fdbfd-f59b-4c38-9b3e-244efff223bc)

![TOTAL SALES BY MONTH, GRAPHLINE](https://github.com/user-attachments/assets/2e287f3a-da20-4220-8f24-e322b181a5bf)


### TOTAL SALES BY MONTH/YEAR IN 2024

PIVOT TABLE
--------------------------

![TOTAL SALES BY Y2024,PIVOT TABLE](https://github.com/user-attachments/assets/8b5f84b0-2ea5-4c2d-b05f-0a2a08a4f3f9)


#### FILTERED CHART FOR THE YEAR 2024
------------

![TOTAL SALES BY Y2024](https://github.com/user-attachments/assets/edb74127-facc-44e2-b908-a11dd46f73f4)

     
![TOTAL SALES BY Y2024,LINE](https://github.com/user-attachments/assets/99872072-600d-42ee-95b4-34b92e9e88ba)


----------------------------------------------------------

#### NO. OF SALES TRANSACTION IN EACH REGION
-----------
![salestransaction pivottable](https://github.com/user-attachments/assets/a254d31e-d158-49ac-be71-a29a4bc005e4)


    


### PROJECT 1B: SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE USING SQL
-----------------------
In this project, I am tasked with analyzing the sales performance of a retail store. I must explore sales data to uncover key insights such as top-selling products, regional performance, and monthly sales trends. This project uses SQL (Structured Query Language) to analyze and extract meaningful insights from a dataset. The objective is to showcase how SQL can query, manipulate, and transform data to solve business problems, uncover trends, and generate actionable findings. Various SQL commands and techniques will be applied with a structured database, including data filtering, aggregation, joins, and subqueries.

#### TOOLS USED
----------
Microsoft SQL Management Studio

  ### EXPLORATORY DATA ANALYSIS 
Write queries to extract key insights based on the following questions.
----------------
 1. Retrieve the total sales for each product category.
 2. Find the number of sales transactions in each region.
 3. Find the highest-selling product by total sales value.
 4. Calculate total revenue per product.
 5. Calculate monthly sales totals for the current year.
 6. Find the top 5 customers by total purchase amount.
 7. Calculate the percentage of total sales contributed by each region.
 8. Identify products with no sales in the last



#### QUERIES AND OUTPUT
--------------
         
            
            1.  --------Retrieve the total sales for each product Category-----
                        SELECT 
                         Product, 
                        SUM(Revenue_sales) AS total_sales
                        FROM  [dbo].[SalesData]
                        GROUP BY 
                        Product;

  ![Q1 SALESDATA](https://github.com/user-attachments/assets/85b185f7-fa67-449f-920f-67d3bae9a6dd)
           
              
              
              
              2.  --------Find the number of sales transactions in each region----
                           SELECT 
                            Region, 
                            COUNT(Orderid) AS num_transactions
                            FROM  [dbo].[SalesData]
                            GROUP BY 
                            Region;

![Q2 SALESDATA](https://github.com/user-attachments/assets/52fd77b3-f58f-476a-a84b-4e698993ac21)

              
               3.    ------Find the highest-selling product by total sales value-----
                          SELECT 
                          product, 
                          SUM(Revenue_sales) AS total_sales_value
                          FROM  [dbo].[SalesData]
                          GROUP BY product
                          ORDER BY 
                          total_sales_value DESC
             
![Q3 SALESDATA](https://github.com/user-attachments/assets/dd8780da-50eb-4ec3-8d1d-68980e141ce5)


                4. -----TOTAL REVENUE PER PRODUCT----------
                        SELECT 
                        Product, 
                        SUM(Revenue_sales) AS total_revenue
                        FROM  [dbo].[SalesData]
                        GROUP BY 
                        Product;
    
   ![Q1 SALESDATA](https://github.com/user-attachments/assets/b9bc4478-13b5-480c-9f1e-49a70dfa2a49)


                5. ----- Monthly sales totals for the current year----
                        SELECT 
                        DATEPART(YEAR, OrderDate) AS year,
                        DATEPART(MONTH, OrderDate) AS month,
                        SUM(Revenue_sales) AS monthly_sales
                        FROM [dbo].[SalesData] 
                        WHERE 
                        DATEPART(YEAR, OrderDate) = DATEPART(YEAR, CURRENT_TIMESTAMP)
                        GROUP BY 
                        DATEPART(YEAR, OrderDate), DATEPART(MONTH, OrderDate)
                        ORDER BY 
                        year, month;
                                            
                                            
                        select OrderDate, sum(Revenue_sales) as Monthlysales_total from  [dbo].[SalesData] 
                        where OrderDate between '2024-01-01' and '2024-12-31'
                        group by OrderDate
                        order by OrderDate

![q5 salesdata](https://github.com/user-attachments/assets/16c8d2f5-8850-4bea-8f73-26e6e517d00b)


                6. --------TOP 5 CUSTOMERS BY TOTAL PURCHASE AMOUNT------
                          SELECT TOP (5) [Customer_Id],
                          SUM(Revenue_sales) AS total_purchases
                          FROM  [dbo].[SalesData]
                          GROUP BY 
                          Customer_Id
                          ORDER BY 
                          total_purchases DESC

![Q6 salesdata](https://github.com/user-attachments/assets/c1a2b7c7-9ffe-412d-99f9-acc84e5ca94b)


                7. -----Percentage of Total Sales each region-----
                         WITH [Region] AS (
                        SELECT [Region], SUM(Revenue_sales) AS Sales
                        FROM [dbo].[SalesData]
                        GROUP BY [Region] )
                        SELECT [Region], (Sales * 100.0 / (SELECT SUM(Revenue_sales) from [dbo].[SalesData] )) AS SalesPercentage
                         FROM Region;

![Q7 SALESDATA](https://github.com/user-attachments/assets/2bbf96dc-ad86-49ad-862a-1fb180a66e6c)




                8.    -------Products with no sales in the last quarter----
                              SELECT 
                              DISTINCT s1.[Product]
                              FROM [dbo].[SalesData] s1
                              LEFT JOIN 
                              [dbo].[SalesData] s2 ON s1.[Product] = s2.[Product] 
                              AND s2.OrderDate >= DATEADD(QUARTER, -1, GETDATE())
                              WHERE 
                              s2.[Product] IS NULL;


![Q8 SALESDATA](https://github.com/user-attachments/assets/f11998f1-d19f-4fb3-8ed4-655b0012d2fd)



  



## PROJECT 1C: SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE USING POWERBI
----------------------
I am creating a dashboard that visualizes the insights found in Excel and SQL. The dashboard should include a sales overview, top-performing products, and regional breakdowns.

### TOOLS USED
Microsoft PowerBI Desktop

### Dashboard Overview
This dashboard provides an interactive and comprehensive view of our sales performance, top-performing products, and regional sales breakdown. By combining insights from Excel analysis and SQL queries, we’ve organized the dashboard into three main sections to support strategic decision-making and uncover trends within our customer base.

1. ### Sales Overview
Purpose: This section summarizes total sales, monthly revenue trends, and average transaction values to give a high-level perspective on sales performance.

Key Metrics: Sum of Total Sales, Average Sales per product, Sum of Quantity, Average of Quantity, Count of OrderID.

Insights:
  1. Sum of Total Sales: This is the total sales revenue generated. It’s calculated by summing up the sales amount across all orders, giving a view of overall sales performance.
  2. Average Sales per Product: This shows the average revenue each product brings in. It’s calculated by dividing the total sales by the number of unique products, providing insight into
      which products generate higher or lower average sales
  3. Sum of Quantity: This metric adds up the total quantity of items sold across all orders. It helps understand overall product demand.
  4. Average of Quantity: This is the average quantity sold per product, calculated by dividing the total quantity by the number of unique products or by the number of orders, depending
      on your analysis. This can show if some products sell in larger or smaller quantities on average.
  5. Count of OrderID: This counts all unique orders placed. It helps you see how many transactions have occurred, offering insight into order volume and customer engagement.

     These metrics can provide a solid foundation for understanding sales volume, product popularity, and average sales per transaction.
       Visual Elements: The monthly revenue and average order value appear as single-value cards to enhance focus.

![Sales Overview](https://github.com/user-attachments/assets/5bfb4501-3182-403e-ac55-396bf079e136)


  2. ### Top-Performing Products
Purpose: Identifying top products helps optimize inventory, promotional efforts, and product development to align with customer preferences.

Key Metrics:  Products by Sales ranking, Total Revenue per Product, total sales of product and quantity, and Monthly Sales Trend

Insights:
  1. Products by Sales Ranking: This ranks products based on their sales performance, typically by total revenue or total units sold. It highlights the top-selling products and can be useful for identifying which products are most popular or generate the highest revenue.
  2. Total Revenue per Product: This is the sum of sales revenue generated by each product. It helps to show which products contribute most to overall revenue, indicating key products for business focus.
  3. Total Sales of Product and Quantity: This metric combines both revenue and quantity sold for each product. It shows the overall financial contribution (total sales) and demand (quantity sold) for each product, giving a complete view of both value and volume performance.
  4. Monthly Sales Trend: This tracks sales over time, broken down by month, to show patterns or seasonal changes in demand. It’s useful for spotting growth trends, declines, and cyclical patterns, which can inform inventory and marketing strategies.
     Visual Elements: The bar chart for sales volume offers an intuitive comparison of top products, and contribution margin metrics appear as KPIs for quick insights.


![montly sales trend](https://github.com/user-attachments/assets/8dfe7d8e-58ac-468f-8046-609aee88f6de)


![product performance](https://github.com/user-attachments/assets/0c36a07e-876f-4e15-98cf-4e82ec707a50)


3. ### Regional Breakdown
Purpose: Regional analysis provides an understanding of geographical sales trends, helping target regions with high potential and adjusting strategies for underperforming areas.

Key Metrics: Sales by Region, Regions by Revenue, and Revenue Distribution Map.

Insights:
 1. Sales by Region: This breaks down sales figures by geographic region. It shows which regions are generating the most sales, helping to identify areas with strong performance or 
    potential growth opportunities.
 2. Regions by Revenue: This metric ranks regions based on the total revenue they generate, allowing a clear comparison of which areas contribute most to the business's revenue. It can 
    also reveal regions with lower performance that may need targeted strategies.
 3. Revenue Distribution Map: This is a visual representation (often a heatmap or colored map) showing revenue across different regions. It helps to quickly see the distribution of 
     revenue geographically, with higher or lower revenue areas distinguished by color gradients. This map can be useful for spotting patterns and regional trends at a glance.


![regional breakdown](https://github.com/user-attachments/assets/981eedaf-cec4-486c-8caa-b9dabb1daa94)


### Conclusion:
Analyzing these metrics offers a comprehensive view of product performance, revealing best-selling items, high-revenue generators, and monthly sales patterns. This data can guide inventory management, pricing strategies, and promotional campaigns to enhance profitability and address gaps in sales performance.



### SPECIAL THANKS TO LITA FOR THIS OPPORTUNITY
