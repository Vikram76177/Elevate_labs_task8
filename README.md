📊 Task 8 — Simple Sales Dashboard (Power BI)

This repository contains the complete submission for Task 8: Simple Sales Dashboard Design from the Data Analytics Internship program. The task focuses on creating a clean, interactive dashboard to visualize sales performance using Power BI.

📁 Project Structure
├── PowerBi_dashboard.pbix  
├── superstore_300.csv 
├── superstore_300_clean.csv     
├── task8.ipynb                   
├── insights.txt
├── Dashboard.jfif
└── README.md                    

🎯 Objective

Build a simple but effective interactive dashboard showing:

Sales trends over time

Sales performance by region

Category-wise sales distribution

Key insights for decision-making

🛠 Tools Used

Power BI Desktop

Python (Pandas) — data validation

Dataset: superstore_300_clean.csv

📌 Dashboard Features

The Power BI dashboard includes:

1️⃣ Line Chart — Sales Over Time

Monthly sales trend using Month-Year format.

2️⃣ Bar Chart — Sales by Region

Comparison of regional performance.

3️⃣ Donut Chart — Sales by Category

Category share in overall sales.

4️⃣ Slicer / Filter

Filter data by Region for interactivity.

📥 Data Preparation

Loaded the Superstore sales dataset.

Converted Order Date → Month-Year.

Checked for missing values or anomalies.

Ensured numeric fields (Sales, Profit) were correctly typed.

📈 Key Insights

(From insights.txt)

Monthly Trend: Sales show fluctuations throughout the year with noticeable monthly peaks (seasonal pattern).

Top Region: East region performs best with total sales of ≈ $41,099.

Top Category: Furniture generates the highest revenue (~$76,172).

Profit Risk: About 6% of orders show negative profit, likely due to returns or heavy discounts, requiring investigation.
