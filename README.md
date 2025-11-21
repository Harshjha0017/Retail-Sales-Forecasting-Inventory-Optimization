🛍️ Retail Sales Forecasting & Inventory Optimization
An End-to-End Business Analytics Project | Python + Power BI

This repository contains a complete business analytics solution designed for retail decision-making.
The project follows a real-world analytics workflow: BRD → FRD → Data Engineering → EDA → Forecasting → Inventory Optimization → Pricing Analytics → Power BI Dashboard.

✅ Project Status
Module	Status
Business Requirements Document (BRD)	✔ Completed
Functional Requirements Document (FRD)	✔ Completed
Data Cleaning & Validation	✔ Completed
Exploratory Data Analysis (EDA)	✔ Completed
Demand Forecasting (ARIMA, Prophet, XGBoost)	✔ Attempted, Evaluated, Documented
Inventory Optimization Engine	✔ Completed
Pricing & Elasticity Analysis	✔ Completed
Power BI Dashboard	🔄 In Progress (Currently Building Interactive Pages)
📌 Project Overview

The goal is to help retail businesses solve critical challenges:

Unpredictable daily demand

Frequent stockouts and overstock situations

Inefficient replenishment planning

Incorrect pricing decisions

Limited visibility across stores, products, and regions

This project delivers a data-driven decision system that supports sales, supply chain, and pricing teams with actionable insights.

🔎 Key Work Completed So Far
1. Business Requirement Document (BRD)

Outlined business goals, scope, stakeholders, KPIs, datasets, and problems such as demand volatility, overstocking, and pricing decisions.

2. Functional Requirement Document (FRD)

Defined system architecture and modules:

Data Intake

Validation & Cleaning

EDA Engine

Forecasting Engine

Inventory Optimization

Pricing & Promotion Analytics

Dashboard Specs

This serves as the blueprint of the entire project.

📊 Python Analysis Completed
✔ EDA Insights

Weak seasonality, high volatility

Category and region differences

Inventory imbalance

Price–demand correlations

XYZ variability and ABC contribution patterns

✔ Forecasting Module

Models tested:

ARIMA

Prophet

XGBoost

All models showed high MAPE, confirming demand is too noisy for reliable forecasting — documented and not deployed.

✔ Inventory Optimization Module

ABC/XYZ classification

Safety stock calculation

Reorder point

Risk flags (Stockout, Overstock, Slow-moving)

Recommended order quantities

✔ Pricing & Promotion Analytics

Price elasticity classification (Elastic vs Inelastic)

Cross-elasticity (Competitor impact)

Product pricing strategy recommendations

Final combined actions per SKU

📊 Power BI (Current Stage)

The Power BI dashboard is currently being developed with a star-schema model:

Fact Table:

fact_sales

Dimension Tables:

dim_product

dim_store

Analytical Tables:

inventory_recommendation

price_elasticity

final_pricing_strategy

Planned Dashboard Pages:

Executive Overview

Sales Trend & Performance

Inventory Health

ABC–XYZ Strategy Matrix

Pricing Intelligence

Final Decision Recommendations

This dashboard will include slicers, KPIs, trend charts, heatmaps, conditional formatting, risk alerts, and drill-down capabilities.

🛠️ Tech Stack

Python: Pandas, NumPy, Scikit-Learn, Matplotlib

Power BI: Data modeling, DAX, interactive visuals

Excel/CSV: Data exports and model inputs

📁 Repository Contents

Python notebook & Py script

All CSV files (fact & dimension tables)

BRD & FRD

Power BI dashboard (once completed)

🎯 Final Purpose

This project demonstrates how a Business Analyst handles:

Real-world requirements

Data engineering

Analytical modeling

Supply chain optimization

Pricing intelligence

BI dashboard development
