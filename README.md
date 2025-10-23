# Mobile Phone Sales Analysis

![Slide1](https://github.com/user-attachments/assets/726805c8-2ab0-4570-a834-3f7c259f4689)


##  Introduction
This Power BI project analyzes mobile phone sales performance across multiple countries, brands, and distributors between 2018 and 2021.

The project’s goal is to analyze sales trends, profitability, and market share distribution to uncover key insights that can guide strategic decisions on product positioning, pricing, and distribution partnerships.

The analysis explores sales patterns, brand performance, and profit trends over time to determine:
* Which markets are most profitable?
  
* Which brands dominate sales?
  
* What operators and distributors drive revenue growth?
  
* How do average unit prices vary across partners?

## Data Source:
The dataset used for this project represents mobile phone sales transactions collected from different regions and business partners. 
* Mobile phone sales transactions Sample Data [https://github.com/C:\Users\USER\Downloads\Business Intel Phone Sales..xlsx)
* Modified Dataset used in this Project [DownloadModifiedDataset](C:\Users\USER\Downloads\Business Intel Phone Sales..xlsx)

## Problem Statement
The analysis aims to address the following key business questions;
1. Which countries generate the highest total sales and profit?
2. How do monthly sales trends change over the years?
3. What are the top-performing brands and distributors?
4. Which operators contribute most significantly to sales by brand?
5. ow does the average unit price differ by distributor?
6. Does discount has an effect on Sales?
7. What growth patterns exist between 2018–2021?
8. Which markets should be targeted for strategic expansion?

## Power BI and Analytics Technical Skills:
+ Project Planning and Documentation
+ Data Gathering
+ Data Cleaning & Transformation (Power Query)
+ Data Modelling & Relationship Management (Star Schema Design)
+ Report Design
+ Data Visualization (Cards, Bars, Lines, Matrix, and KPIs)
+ Advanced DAX Calculations
+ Page Navigation and Button
+ Business and Analytics Reporting
+ Performance Optimization
+ Deployment and Power BI Service
+ Scalability
+ Storytelling through Data Visualization
+ Feedback and Continuous Improvement
  
## Data Modelling
The data model follows a star schema, consisting of:

* 1 Fact Table: containing sales transactions, profit, and quantity data.

* 4 Dimension Tables: Country, Brand, Operator, and Distributor.

## A Calendar Table  was also created using DAX for time intelligence functions (e.g., monthly and yearly comparisons).
Relationships were defined using primary and foreign keys to ensure optimal model performance.
<img src="https://github.com/<img width="1390" height="652" alt="Screenshot 2025-10-23 011925" src="https://github.com/user-attachments/assets/6bcf7c58-8ec3-40dc-9d1e-d34b08a04ad9" />

## Report Design and Visualization
The dashboard was designed with a deep blue and white professional theme for readability and corporate appeal.

* The layout background was designed in PowerPoint, imported into Power BI as a canvas background.

* Two report pages were developed:

1 Summary Page – for overall business performance.

2  Breakdown Page – for detailed analysis by brand, operator, and distributor 
<img src=<img width="1203" height="663" alt="Screenshot 2025-10-23 012808" src="https://github.com/user-attachments/assets/9e2f0cbc-3b70-4d4e-b6a8-5e4cc2beebc4" />
  
5 pages were created; Home, Consolidated, Stationery, Cosmetics and Electronics. 
_Home_ page is the landing page while _Consolidated_ has the general report without filter while other pages has filtered reports accroding to their page name.
On each page, the new card visual is used to hold Total Sales, Gross Sales and Profit, Line Chart is used for the series analysis while a column and bar chart are adopted for the Continental and Country analysis respectively. The last image is the button for page navigation. 

| Visuals             |  Visuals |
:-------------------------:|:-------------------------:
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Card1.PNG" width=90% height=90%>|<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/button1.PNG" width=40% height=40%> 
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/columnbarchart.PNG" width=60% height=60%> |<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Linechart.PNG" width=100% height=100%> 

## Analytics and Insights
The data analysis revealed that;

1. There is a zig-zag trend of profit across the months, however, October records the highest profit of ($3.74M) which is 15% of the total profit and April records the least profit of ($1.4M), 6% of total profit
2. There exist an increase in profit from 2013 to 2014 with a ration of 4:6
3. Q4 record the highest profit of ($8.4M) with Q1 with the lowest ($5M), this shows steady increase in profit across the quarter from 1 to 4
4. The most and least profitable product category are Stationery and Cosmetics which amounts to 44% and 28% of the total profits respectively 
5. By region continent is intended, therefore Haut supermarket makes the most sales from America region ($98M) with 47% of the total Gross Sales
6. This is achieved with the help of the slicer; which shows that product with discount result to 96% of the total Gross sales while only 4% don't have discount, with **High** band of discount amounting to 41% of the Gross Sales
7. Africa pull 9% of the total Gross sales and 6% of the total Profit from the 202,286 Units solds from South Africa and Nigeria. This is can be visualised when clicking on Africa in the column chart 
8. France is the most profitable Country among the Haut Stores with 20% ($4.9M) of the total profit

![ConsolidatedDashboard](https://github.com/Abdur-RasheedAde/Haut_Sales_Analysis/blob/main/Page2Consolidated.PNG)

## Conclusions and Recommedations

1. Haut needs to conduct market analysis to increase sales in Q1 and Q2 and offer seasonal products that appeal to customers in the first half of the year
2. Haut’s management should continue their market strategy that leads to higher profits and better customer satisfaction
3. The cosmetics product category demands more research and development to boost its sales and profitability
4. Promotions (discounts) drive most of the sales in Haut stores, making them competitive in the dynamic market. Therefore, other promotional and marketing strategies should be implemented to enhance sales and profit
5. Products in Africa and China stores should be tailored to the specific needs of these markets through careful research

## Deployment to Power BI Service
This Report is deployed to Power BI service from my Microsoft developer account and publish to the web for everyone to have access to it.
[HautSupermarketAnalysis](https://app.powerbi.com/groups/me/reports/66ab0071-4b25-41c8-99fd-fd006603aacd/ReportSection6239a8326550e132bae6?ctid=32796be2-60fb-4da2-8d26-06e5938e6e6b&experience=power-bi)  

To Open a developer Microsoft account, kindly check this article [OpenMicrosoftdeveloperaccount](https://techcommunity.microsoft.com/t5/educator-developer-blog/register-for-microsoft-365-and-power-apps-developer-account-with/ba-p/3490280)

Thanks for taking time to go through this report! 🤝



