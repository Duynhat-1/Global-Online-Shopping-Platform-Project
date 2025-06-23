# Global Online Shopping

### Dashboard Link : https://app.powerbi.com/groups/me/reports/d0bf1c16-3964-46cb-92a1-9b896c506563?ctid=af1f3753-3925-4e6f-949b-97c007320803&pbi_source=linkShare

## Table of content
- [Project overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Data analysis](#data-analysis)
- [Conclude](#conclude)
-------------------
### Project overview

This project aims to analyze global online shopping data to uncover patterns in customer behavior and product performance that can support strategic decision making in international e-commerce.

The customer analysis focuses on building customer profiles based on their purchasing frequency, evaluating whether frequent customers contribute more to overall revenue and profitability, and identifying the most profitable customer segments across different years and regions. It also explores how customers are distributed across countries.

The product analysis examines which countries generate the highest sales, identifies the most profitable product categories by year, and analyzes the relationship between product price changes and sales volume at the daily level. Additionally, it investigates the average delivery time across different districts to highlight potential areas for operational improvement.

The insights gained from this analysis will help inform pricing strategies, customer segmentation, and logistics optimization for global online retail businesses.

### Data Sources

Global super store: The dataset used for this analysis is the "global_superstore_2016.xlsx" file containing detailed information about transactional data for a global online retail business, including information on orders, customers, products, sales, profits, regions, and shipping details

### Tools

- Excel - Data Sources 
- PowerBi - Data cleaning, Data analysis, Creating reports

### Data Cleaning

During the initial data preparation phase, I completed the following tasks:

- Loaded and inspected the data by check "column distribution", "column quality" & "column profile" options.
- Handled missing values
- Cleaned and formatted the data

### Exploratory Data Analysis 

EDA involved exploring data to answer key questions:

Customers Analysis:

- What are the customer profiles based on their purchase frequency?
- How often does each customer make a purchase?
- Do frequent customers contribute more to overall revenue?
- Are frequent customers also more profitable? What are the profit margins across different customer groups?
- Which customer segments generate the most profit in each year?
- How are customers distributed across different countries?

Product Analysis:

- Which countries generate the highest sales?
- What are the top five most profitable product categories each year?
- How do product price changes impact sales — is there an increase in daily sales when prices drop?
- What is the average delivery time across districts?

### Data analysis

- Overview

![alt image](https://github.com/Duynhat-1/Global-Online-Shopping-Platform-Project/blob/8741fb9e12287b726e35bf17235837539f036e5c/Overview.png)

🚩 Office Supplies dominate unit sales (108K units) but not profit margin (under 3%). Technology has fewer units sold (35K) but better profit margin

✅ The strong sales in Office Supplies could mask lower profitability; consider strategies to upsell or focus more on technology segment

🚩 Asia Pacific is the top-selling market (49K units), but Europe delivers higher profit margin.

✅ Regional pricing or cost differences may explain Europe’s better margin despite lower volume compared to Asia Pacific. Company should boots technology segment to the Europe and USCA market

🚩Standard Class shipping accounts for the largest volume (60%+) and is the most profitable shipping method.

✅ Shipping strategies (Standard Class) align well with profit goals. Consider maintain focus on cost-effective delivery.

🚩Return rate is low overall at ~1.23%, indicating good customer satisfaction or product fit.

✅ Can track on the product segment that has the most return and make some improvement in both quality and service to the customer who return the product

- Products 

![alt image](https://github.com/Duynhat-1/Global-Online-Shopping-Platform-Project/blob/8741fb9e12287b726e35bf17235837539f036e5c/Products.png)

🚩 Technology category delivers the highest net profit (45.23% of total), despite lower unit sales compared to Office Supplies.

🚩 Furniture gets the largest share of discounts (41.23%) — might contribute to margin pressure.

✅ Discounts on Furniture may be eroding profitability; reassess discounting strategy or cost base. Company might allocate more discount or event to boots sales in technology segment

🚩 Office Supplies have the most returns (1,348 units) — indicates possible quality or expectation mismatch issues.

✅ Return rates on Office Supplies warrant attention — consider analyzing SKUs or suppliers with high return rates.

🚩 Top sub-categories for profit: Copiers (5.19% margin) and Phones (3.32% margin).

✅ Focus on promoting high-margin sub-categories (e.g., Copiers, Phones) more aggressively.
- Customers 

![alt image](https://github.com/Duynhat-1/Global-Online-Shopping-Platform-Project/blob/8741fb9e12287b726e35bf17235837539f036e5c/Customers.png)

🚩 The Consumer segment contributes the most purchases (51.68% units) and the highest net profit (51.06%).

🚩 The Home Office segment has the lowest purchased share (18.28%) but shows the highest profit margin (2.44%).

🚩 Corporate segment has the lowest profit margin (2.35%) among the segments their purchase volume is higher than Home Office segment.

✅ The Consumer segment is driving both sales and profits, but Home Office customers, though smaller in volume, are more profitable on a per-unit basis. The company consdier focus more on Home office customers

✅ Company should explore why Corporate’s profit margin lags — possibly due to higher discounting or operational costs.

🚩Customer base is concentrated in the US (2501 customers), far ahead of other countries like France (679) and Mexico (668).

### Conclude

CUSTOMERS:

- Frequent customers clearly contribute more to overall revenue. However, not all frequent buyers deliver strong profit margins — e.g., some have negative or very low margins (Harry Greene, Sapphira Shifley).

-> Should monitor customer-level profitability closely to avoid over-serving low-margin accounts. Focus incentives and loyalty efforts on those who are both frequent and profitable.

- The Home Office segment consistently shows the highest profit margin (2.44%), though its purchase volume is the lowest.

-> Yearly analysis should continue to track which segment sustains this trend and why (e.g., higher-margin products, lower discounts).

- The United States dominates the customer base (2501 customers), followed distantly by France, Mexico, and Australia.

-> This concentration suggests growth opportunities in under-penetrated countries and a need to diversify risk across geographies.

PRODUCTS:

-  United States leads in sales volume, driven by large customer base concentration.

-> Expansion efforts might prioritize scaling successful US strategies in Europe or Asia Pacific.

-  Sub-categories like Copiers (5.19% margin) and Phones (3.32% margin) are consistently among the most profitable.

-> Focus on promoting these categories and expanding their market reach.

-  The average shipping time is 3.97 days, with some regional variation (e.g., faster in Central Asia, slower in Central America).

-> Company should aim to standardize delivery times across regions to improve customer satisfaction.



