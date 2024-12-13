# Electronic Consumer Goods Business Insight Dashboard

## Introduction 
Project Overview: The project delved into datasets of a hardware company that supplies various computer hardware categories to e-commerce and brick-and-mortar customers across multiple countries and regions. The dashboard explored sales data from over 1 million records and extracted insights from multi-faceted dimensions, such as finance, marketing, sales, supply chain, etc. The dashboard included multiple filter slicers, region/market, product segment/category, customers and multiple years (2019 to 2022). The two benchmark criteria for KPI are ‘VS last year’ and ‘VS target’.


## Tools & Platform 
Power BI Desktop, MySQL, Dax Language, Power Query, Dax Studio (for optimizing the report), Power BI Service, Excel


## Key Steps:
1.	Connected to MySQL database and loaded data to Power BI. Introduced 3 dimension tables (product, market, customer) and 7 fact sales tables(monthly_sales, monthly_ forecast, gross price, pre-invoice deduction, post-invoice deduction, freight cost, manufacturing cost). Imported 3 Excel fact tables (operating expense, market share and targets)
2.	Performed data cleaning and ETL in power query 
3.	Bulit data models (created star schema and snowflake schema diagram), calculated measures and performed data validation using Excel
4.	Created dashboards for different departments


## Dashboards Content Highlights:
Finance: created P&L statement and its dynamic yearly trend, tracked KPI (net sales, gross margin % and net profit %). benchmarked P&L metrics against last year /target

![finance view!](https://github.com/user-attachments/assets/f1064784-1674-48a4-a9e3-68e41bcca840)


  

Sales: created key metrics (net sales, gross margin(%), and quantity) for customers and products, benchmarked against last year. developed a scatter plot to show customer performance metrics against two benchmarks. built a parameter (tolerance gap) to filter customer groups that lag behind the benchmark 

![Sales view!](https://github.com/user-attachments/assets/b8f53bf5-1d13-4c65-ab0d-c21f12ec2a32)





Marketing: built net sales, gross margin(%), and net profit(%) across regions/markets and products. Examined operation expense and net profit in general
Supply chain: tracked KPI of net error (%), absolute error(%), sales forecast accuracy %, and yearly trend. Benchmarked forecast accuracy against last year's performance across customers and products
Executive view: Provided key insights by sub-zone and the company's yearly growth trend in market share. Analyzed revenue breakdown by product division and sales channel. Examined the PC market share  of the company against main players. Highlighted top 5 customers and top 5 products by revenue

![Marketing view!](https://github.com/user-attachments/assets/b8f53bf5-1d13-4c65-ab0d-c21f12ec2a32)



Supply chain: tracked KPI of net error (%), absolute error(%), sales forecast accuracy % and yearly trend. Benchmarked forecast accuracy against last year's performance across customers and products
![Supply chain view!](https://github.com/user-attachments/assets/b8f53bf5-1d13-4c65-ab0d-c21f12ec2a32)


Executive view: Provided key insights by sub-zone and the company's yearly growth trend in market share. Analyzed revenue breakdown by product division and sales channel. Examined the PC market share  of the company against main players. Highlighted top 5 customers and top 5 products by revenue


![Executive view!](https://github.com/user-attachments/assets/09a6e03e-0352-4f2d-99d8-02dd51c9c560)





