# customer-churn-dashboard-power_bi
"Customer churn analysis dashboard built in Power BI with DAX-based risk segmentation"
# Customer Churn Analysis Dashboard

## Overview
An interactive Power BI dashboard analyzing customer churn patterns across 5,630 customers, identifying key drivers of churn and segmenting customers by risk level to support retention strategy.

## Business Problem
Telecom companies lose significant revenue to customer churn. This project analyzes customer behavior, contract types, and service usage patterns to identify which customer segments are at the highest risk of churning, enabling the business to prioritize retention efforts where they will have the most impact.

## Dataset
Source: Telco Customer Churn Dataset (Kaggle) - https://www.kaggle.com/datasets/blastchar/telco-customer-churn
Contains 7,000+ customer records including demographics, account information, services subscribed, and churn status.

## Tools and Techniques
Power BI for interactive dashboard design
DAX for custom measures including Churn Rate, Retention Rate, Average Tenure, and Risk Classification
Power Query for data cleaning, transformation, and shaping

## Key Insights
Overall churn rate is 19 percent, with 1,089 of 5,630 customers churned
Month-to-month contracts account for the majority of churn at 875 customers, compared to 166 for one-year contracts and 48 for two-year contracts, suggesting contract length is a strong retention lever
New customers with 0 to 6 months of tenure churn at the highest rate, indicating onboarding and early engagement is a critical retention window
Built a custom risk classification measure in DAX, flagging 673 customers as high risk based on tenure, contract type, and service usage patterns
Customers without Online Security add-ons show a different monthly charge distribution tied to elevated churn risk, indicating a potential upsell or retention opportunity

## Business Recommendation
Focus retention campaigns on new, month-to-month customers in their first six months. This segment shows the highest concentration of churn risk and the greatest opportunity for intervention.

## Dashboard Preview


![Dashboard Overview](Screenshot%20(11)

.png)


![Churn Rate by Tenure Band](Screenshot%20(12)

.png)

## Files
customer churn dashboardd.pbix - Full Power BI report file

## Project Date
September 2026
