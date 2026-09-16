# 📊 Customer Churn Analysis Dashboard

**Interactive Power BI dashboard with DAX-based risk segmentation to identify and prioritize at-risk customers for retention.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=flat)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

---

## 📌 Overview

An interactive Power BI dashboard analyzing churn patterns across **5,630 telecom customers**, identifying the key drivers of churn and segmenting customers by risk level using custom DAX measures — enabling the business to prioritize retention efforts where they matter most.

## 🎯 Business Problem

Telecom companies lose significant revenue to customer churn. This project analyzes customer demographics, contract types, and service usage patterns to identify which segments are at the highest risk of churning, so retention efforts can be focused for maximum impact.

## 🖼️ Dashboard Preview

| Overview | Churn by Tenure Band |
|---|---|
| ![Dashboard Overview](Screenshot%20(11).png) | ![Churn Rate by Tenure Band](Screenshot%20(12).png) |

![Risk Segmentation View](Screenshot%20(13).png)

## 🗂️ Dataset

7,000+ customer records including demographics, account information, subscribed services, and churn status. Raw file: [`telco_churn_unclean.csv`](telco_churn_unclean.csv).

## 🛠️ Tools & Techniques

| Tool | Purpose |
|---|---|
| **Power BI** | Interactive dashboard design and visualization |
| **DAX** | Custom measures — Churn Rate, Retention Rate, Average Tenure, Risk Classification |
| **Power Query** | Data cleaning, transformation, and shaping |

## 💡 Key Insights

- **Overall churn rate is 19%** — 1,089 of 5,630 customers churned
- **Month-to-month contracts drive the majority of churn** (875 customers) vs. one-year (166) and two-year (48) contracts — contract length is a strong retention lever
- **New customers (0–6 months tenure) churn at the highest rate**, marking onboarding and early engagement as a critical retention window
- **Custom DAX risk classification measure** flags **673 customers as high risk**, based on tenure, contract type, and service usage
- **Customers without Online Security add-ons** show a monthly charge pattern tied to elevated churn risk — a potential upsell/retention opportunity

## ✅ Business Recommendation

Focus retention campaigns on **new, month-to-month customers in their first six months** — the segment with the highest concentration of churn risk and the greatest opportunity for intervention.

## 📁 Files

| File | Description |
|---|---|
| [`customer churn dashboardd.pbix`](customer%20churn%20dashboardd.pbix) | Full Power BI report |
| [`telco_churn_unclean.csv`](telco_churn_unclean.csv) | Raw dataset |

## 🚀 How to Use

1. Download `customer churn dashboardd.pbix`
2. Open in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads)
3. Explore the report pages and use slicers to drill into segments by contract type, tenure, and risk tier

## 📅 Project Date

September 2026

## 👤 Author

**Sanjay Rawat**
[LinkedIn](https://linkedin.com/in/sanjay-rawat-a0b157290) · [GitHub](https://github.com/sr165208-hue)
