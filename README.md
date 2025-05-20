📊 Marketing Campaign Performance Analysis
This project provides a comprehensive analysis of digital marketing campaigns using Python (Jupyter Notebook) for data processing and Power BI for visualization. It helps uncover insights into campaign efficiency, ROI, and conversion performance across multiple channels.

🧰 Tools & Technologies
Python (Jupyter Notebook) – Data cleaning, transformation, and KPI calculation

Power BI – Interactive dashboards for executive insights and diagnostics

📁 Project Structure
graphql
Copy
Edit
├── Marketing_Analysis.ipynb      # Python notebook for data processing and KPI calculation
├── merged_marketing_data.csv     # Cleaned dataset exported for Power BI
├── Marketing_Dashboard.pbix      # Power BI dashboard with visuals and slicers
├── README.md                     # Project overview and usage guide
📌 Datasets Used
Marketing Spend Data – Channel-wise campaign spend over time

Sales Performance Data – Leads, conversions, and revenue generated

📐 KPIs Calculated (in Python)
CPL (Cost Per Lead) = Spend / Leads

CPA (Cost Per Acquisition) = Spend / Conversions

ROAS (Return on Ad Spend) = Revenue / Spend

Conversion Rate (%) = (Conversions / Leads) × 100

These metrics were merged and exported as merged_marketing_data.csv for Power BI analysis.

📊 Power BI Dashboard Overview
🔸 Page 1: Executive Summary
Total Spend, Revenue, ROAS, CPA, and Conversion Rate cards

Revenue by Channel (Bar Chart)

ROAS Trends over Time (Line Chart)

Bubble Chart: Spend vs Revenue vs ROAS

Campaign-level summary table

Slicers for Channel & Campaign filters

🔹 Page 2: Deep Dive & Diagnostics
Filters: Date, Channel, Campaign

ROAS by Campaign (Line Chart)

Campaign-wise Spend (Bar Chart)

Detailed campaign performance table

Matrix view: Revenue by Channel and Campaign

🚀 How to Run This Project
Open Marketing_Analysis.ipynb in Jupyter Notebook
→ Run all cells to generate merged_marketing_data.csv

Open Marketing_Dashboard.pbix in Power BI Desktop
→ Load the CSV and explore insights via filters and visuals

✅ Key Insights Uncovered
High-performing channels (e.g., Google Ads, LinkedIn) have strong ROAS

Some campaigns have high CPA, requiring budget optimization

ROAS and conversion rates vary significantly across channels and time

The dashboard enables real-time exploration by campaign and channel

