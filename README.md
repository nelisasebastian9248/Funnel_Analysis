📊 User Funnel Performance Analysis
📌 Project Overview

This project performs an end-to-end user funnel analysis to understand how users move through key stages of an e-commerce journey — Browse → Add to Cart → Checkout → Purchase.
The goal is to identify conversion drop-offs, analyze revenue contribution, and uncover behavioral patterns across channels, devices, regions, and time.

The analysis combines Python-based exploratory data analysis (EDA) with an interactive Power BI dashboard to deliver actionable business insights.

🎯 Business Problem

User drop-offs across funnel stages directly impact revenue.
This project answers questions such as:

Where do users drop off the most in the funnel?

How strong are conversions between each stage?

Which channels, devices, and regions perform better or worse?

How does user behavior translate into revenue outcomes?

🧩 Funnel Stages Defined

Browse: User views products

Add to Cart: User adds item to cart

Checkout: User initiates checkout

Purchase: User completes transaction

🛠️ What I Did (Step-by-Step)
1️⃣ Data Preparation & Cleaning (Python)

Loaded raw funnel event data using Python

Cleaned missing and inconsistent values

Ensured correct event sequencing per user

Aggregated user-level funnel progression

Prepared summary tables for conversion and drop-off analysis

2️⃣ Exploratory Data Analysis (EDA)

Using Python (Pandas, NumPy, Matplotlib,Seaborn):

Calculated stage-wise user counts

Computed conversion rates and drop-off rates

Analyzed revenue distribution across channels

Evaluated device-level and region-level performance

Validated trends before dashboarding

3️⃣ Funnel Metrics & KPIs

Key metrics derived:

Total Users

Overall Conversion Rate

Stage-wise Conversion Rates

Drop-off Percentage

Total Revenue

Revenue by Channel & Region

4️⃣ Power BI Dashboard Development

Built an interactive Power BI dashboard with:

Funnel visualization showing user drop-offs

Stage-to-stage conversion breakdowns

Revenue by Channel, Region, and Device

KPI cards for quick performance tracking

Slicers for Date, Device, Channel, and Region

The dashboard enables stakeholders to quickly explore performance drivers and bottlenecks.

📊 Power BI Dashboard Preview
<img width="2201" height="1194" alt="image" src="https://github.com/user-attachments/assets/73282140-b96d-47e1-8188-e3a067eb3116" />


🔍 Key Insights (Example)

Significant drop-off observed between Checkout → Purchase

Mobile users show higher drop-off compared to desktop

Email and Google Ads contribute the highest revenue

Conversion performance varies noticeably by region

Despite high traffic, overall funnel conversion remains low, indicating optimization opportunities


📂 Project Structure
Funnel_Analysis/
│
├── funnel.ipynb                 # Python EDA and funnel calculations
├── main.py                      # Supporting analysis scripts
├── funnel_analysis_data.csv     # Input dataset
├── funnel_analysis_report.xlsx  # Summary metrics and outputs
├── Funnel_Analysis_Dashboard.pbix  # Power BI dashboard
├── images/
│   └── dashboard_overview.png   # Dashboard screenshots
├── README.md

🧰 Tools & Technologies

Python: Pandas, NumPy, Matplotlib

Power BI: DAX, interactive dashboards, slicers

Excel: Metric validation and reporting

Git & GitHub: Version control and project sharing

🚀 Outcome & Value

This project demonstrates how data can be transformed into clear, decision-ready insights by combining analytics and visualization.
It highlights funnel inefficiencies and provides a foundation for conversion rate optimization and revenue growth strategies.
