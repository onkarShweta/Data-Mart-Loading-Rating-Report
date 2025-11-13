# Data-Mart-Loading-Rating-Report
🎯 1. Project Title / Headline
Data-Mart-Loading-Rating-Report

An interactive Power BI dashboard built on a custom Data Mart to compare and analyze credit ratings from Moody’s, S&P, and Fitch. It highlights rating trends, vendor differences, and historical changes using SCD Type-2 logic.

📌 2. Short Description / Purpose

The CreditSphere dashboard provides a unified, visualized layer of credit rating information sourced from three major rating agencies.
It helps auditors, analysts, and financial stakeholders quickly assess rating movement, vendor disagreement, and trend patterns across securities and vendors.

🛠 3. Tech Stack

The dashboard was developed using the following technologies:

📊 Power BI Desktop – Visualizations, KPIs, trends

📂 Excel / Power Query – Data cleaning, merging, SCD logic

🧠 DAX (Data Analysis Expressions) – KPI measures & calculations

🧩 Data Modeling – Vendor → Ratings → Time relationships

📁 File Formats – .pbix, .xlsx, .png

📁 4. Data Source

Multi-vendor rating feeds from:

Moody’s

S&P

Fitch

Each record contains:
Security ID, Vendor ID, Rating Type, Rating Code, Rating Date, Exchange Code, Source Feed ID

This raw data is transformed into a structured SCD Type-2 Data Mart capturing rating history (Start Date, End Date, Previous Rating).

⭐ 5. Features / Highlights
🔍 Business Problem

Organizations need a consolidated way to:

Compare vendor rating differences

Track upgrades/downgrades

Identify rating patterns

Analyze historical movements

Raw vendor feeds do not offer this clarity.

🎯 Goal of the Dashboard

To build a centralized visual tool that:

Displays vendor-wise rating insights

Tracks SCD Type-2 historical changes

Highlights rating stability/volatility

Enables forecasting using rating trends

📊 Walkthrough of Key Visuals

KPI Cards
Total Ratings, Changed Ratings, Upgrade %, Vendors Count

Rating Trend Line Chart
Shows rating changes over time + forecasting

Vendor Comparison Bar Chart
Moody’s vs S&P vs Fitch rating distribution

Rating Type Distribution
Long-term, Short-term, Recovery, Viability

SCD History Table
Previous Rating → Current Rating → Start/End Dates

Dynamic Filters (Slicers)
Vendor, Year, Rating Type, Security ID

📈 Business Impact & Insights

⚡ Faster audit review & anomaly detection

🧩 Better vendor comparison & agreement analysis

📉 Improved investment risk assessment

🔮 Forecasting helps anticipate rating shifts

📊 Clear visibility of rating stability across vendors

🖼 6. Screenshots / Demo
https://github.com/onkarShweta/Data-Mart-Loading-Rating-Report/blob/main/Data%20Mart%20Loading%20%26%20Rating%20Report_snapshot.png
