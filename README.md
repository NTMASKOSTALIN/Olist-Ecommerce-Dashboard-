<img width="1599" height="899" alt="Executive Overview (2)" src="https://github.com/user-attachments/assets/141abda0-b81b-453b-80eb-61ab6f532e86" /># Olist-Ecommerce-Dashboard-

## Project Title:
Customer Retention & Revenue Optimization in Olist E-Commerce Platform

## Problem Statement:
Olist's transaction data reveals a critical business challenge: the majority of customers never return after their first purchase, representing significant lost lifetime value and revenue leakage. This project investigates the operational and experiential factors driving this churn — including delivery failures, product dissatisfaction, and seller unreliability — and quantifies their financial impact on the platform.
By analysing customer transactions, delivery performance, review behaviour, and seller metrics, this project delivers data-driven recommendations to improve customer retention, increase lifetime value, and optimise platform revenue.

## Project Links:

GitHub: https://github.com/NTMASKOSTALIN/Olist-Ecommerce-Dashboard-

Tableau: https://public.tableau.com/views/OlistECommerceDashboard_17810122103490/CustomerRetention?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Business Objective:
Identify the key operational and experiential drivers of customer churn on the Olist platform, and provide actionable recommendations to increase repeat purchase rates, optimise delivery performance, and maximise customer lifetime value (CLV).

## Hypothesis:
Delivery delays and poor post-purchase experience — reflected in low review scores — are the primary drivers of customer churn on the Olist platform, with customers who experience delays beyond a critical threshold being significantly less likely to return.

## Business Questions:
**1. Customer Retention & Churn**
   
• What percentage of customers are one-time vs. repeat buyers?

• After how many days do customers typically stop purchasing?

• Which customers show early signs of churn based on recency?

**2. Revenue & Customer Value**
   
• Do repeat customers contribute disproportionately more revenue than one-time buyers?

• Which customer segments generate the highest lifetime value?

• How does basket size (AOV) and purchase frequency influence total revenue?

**3. Delivery Performance**
   
• Is there a measurable delay threshold beyond which customer satisfaction drops sharply?

• Which regions and sellers are responsible for the highest delivery delays?

**4. Customer Experience**
   
• What factors — delay, price, product type — most strongly predict low review scores?

• Do customers who leave low ratings have measurably lower repeat purchase rates?

**5. Seller & Product Performance**
    
• Which sellers contribute most to delayed, cancelled, or poorly rated orders?

• Which product categories drive repeat purchases vs. high dissatisfaction?

## KPIs

**1. Customer Retention**
   
• Repeat Purchase Rate

• Churn Rate

• Purchase Frequency

• Avg Days Between Purchases

• Time to Churn

**2. Revenue & Customer Value**
   
• Total Revenue

• Average Order Value (AOV)

• Revenue per Customer

• CLV Proxy

• One-time vs. Repeat Revenue Split

• Revenue by RFM Segment

**3. Delivery Performance**
   
• Avg Delivery Time

• Delivery Delay Rate

• Avg Delay Duration

• Delay Threshold Impact

• Regional Delay Rate

**4. Customer Experience**
   
• Average Review Score

• Low Rating Rate

• Review Score vs. Delivery Status

• Repeat Rate by Review Score

• Review Score by Product Category

**5. Seller Performance**
    
• Seller Delay Rate

• Seller Average Rating

• Seller Cancellation Rate

• Seller Revenue Contribution

**6. Product Performance**

• Repeat Purchase Rate by Category

• Low Rating Rate by Category

• Revenue Contribution by Category

**7. Advanced**
    
• RFM Segmentation

• Retention Cohort Rate

• Early Churn Signals

## Process

**Data Extraction & Preparation (SQL):** Imported and integrated 9 relational Olist e-commerce datasets containing customer, order, payment, review, seller, product, and geolocation information. Performed comprehensive data profiling, data quality audits, duplicate checks, null value analysis, referential integrity validation, timeline anomaly detection, and business rule verification. Cleaned and standardized data using CTEs, Window Functions, CASE statements, Joins, and Aggregations to create an analytics-ready master dataset.

**Exploratory Data Analysis (Python):** Conducted univariate, bivariate, and time-series analysis to evaluate customer purchasing behavior, delivery performance, review patterns, payment trends, and seller effectiveness. Applied outlier treatment, feature engineering, and customer-level aggregations to identify key drivers of churn, customer satisfaction, and revenue generation.

**Advanced Analytics:** Developed RFM Segmentation, Cohort Retention Analysis, Customer Lifetime Value (CLV), churn indicators, and delivery delay impact analysis. Tested the hypothesis that delivery delays and poor customer experience drive churn, discovering that while delays significantly reduced satisfaction scores, customer churn was primarily driven by structural purchasing behavior rather than poor experience alone.

**Dashboard Development (Tableau):** Designed a 6-page interactive Tableau dashboard featuring Executive Overview, Customer Retention, Revenue & CLV, Delivery Performance, Customer Experience, and Seller & Product Analytics. Developed 30+ KPIs including Churn Rate, Repeat Purchase Rate, CLV, Average Order Value, Delivery Delay Rate, Review Scores, Revenue Contribution, and Seller Performance metrics.

**Business Recommendations:** Identified that 96.9% of customers were one-time buyers and that VIP and Loyal customers generated approximately 75% of total revenue. Recommended targeted retention campaigns, loyalty programs, personalized cross-selling strategies, seller performance monitoring, logistics optimization initiatives, and win-back campaigns to improve customer retention and maximize lifetime value.

<img width="1599" height="899" alt="Executive Overview" src="https://github.com/user-attachments/assets/51901ced-4e15-486a-81aa-9d07fa1c6d76" />

<img width="1599" height="899" alt="Customer Retention" src="https://github.com/user-attachments/assets/bd1da2a5-0f12-435f-833f-5be7c95fddf7" />

<img width="1599" height="899" alt="Revenue   CLV" src="https://github.com/user-attachments/assets/9ab6d565-f2fd-4057-acf2-1b7f55f53a05" />

<img width="1599" height="899" alt="Delivery Performance" src="https://github.com/user-attachments/assets/3fc67c61-3c30-426b-ae51-3cf667c4e6a2" />

<img width="1599" height="899" alt="Customer Experience" src="https://github.com/user-attachments/assets/1e94f03d-9de6-4ae9-af16-cfc4c03022fa" />

<img width="1599" height="899" alt="Seller   Product" src="https://github.com/user-attachments/assets/fc314517-4ed9-4eea-a61e-a1f6880e8da8" />

## Key Insights:

1. **Customer Retention Challenge:** 96.9% of customers were one-time buyers, while only 3.1% returned for repeat purchases, highlighting a significant customer retention opportunity.

2. **Revenue Concentration:** VIP and Loyal customer segments contributed approximately 75% of total platform revenue, demonstrating that a small group of high-value customers drives the majority of business performance.

3. **Delivery Experience Impact:** Average review scores dropped from 4.29 for on-time deliveries to below 2.0 for severely delayed orders, confirming that logistics performance strongly influences customer satisfaction.

4. **Churn Hypothesis Outcome:** Despite poor delivery experiences reducing satisfaction, churned customers still maintained an average review score of 4.15/5, indicating that customer churn is driven more by structural purchasing behavior than poor customer experience alone.

5. **Operational Revenue Leakage:** Identified payment-processing and fulfillment anomalies that resulted in shipped but unpaid orders, exposing preventable revenue leakage and operational control gaps.

6. **Customer Sentiment Issue:** Analysis revealed that 61.9% of reviews submitted before delivery were 1-star ratings, uncovering an automated communication issue negatively affecting customer perception.

7. **Marketplace Concentration:** Seller and customer activity were heavily concentrated in São Paulo (SP), suggesting geographic dependency and potential delivery challenges for distant regions.

## Conclusion:

The Customer Retention & Revenue Optimization dashboard provides a comprehensive view of customer behavior, revenue performance, delivery operations, and seller effectiveness across the Olist marketplace.

The analysis identified customer retention as the primary business challenge, with nearly all customers purchasing only once despite generally positive satisfaction levels. Findings showed that while delivery delays significantly affect customer experience, improving retention requires strategies beyond operational improvements alone.

The project enables stakeholders to monitor customer lifetime value, identify high-value customer segments, detect operational risks, optimize logistics performance, and implement targeted retention, cross-sell, and win-back initiatives to maximize long-term revenue growth.
