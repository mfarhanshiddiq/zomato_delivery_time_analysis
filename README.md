📦 Zomato Delivery Time Analysis

📌 Project Overview
Zomato is a food delivery platform whose performance is highly dependent on delivery speed. The longer the delivery time, the higher the risk of customer dissatisfaction, low ratings, or churn.
The goal of this project was to identify the operational factors that most impact delivery times, so the team could take data-driven action.
Benefits: Helping the operations team reduce average delivery times, increase customer satisfaction, and optimize courier resource allocation.

🎯 Business Problem
From approximately ~46,000 delivery data (February–April 2022), the average delivery time was 26.3 minutes — but the spread was wide (10–54 minutes). Zomato doesn't yet know the exact factors that determine delivery speed, making it difficult to take targeted operational action.

Business Question
1. External Conditions During Delivery
How do external conditions (weather, traffic congestion, and festivals/public holidays) affect delivery times, and how significant is the impact quantitatively?

2. Operational & Courier Factors
Which operational delivery factors (number of multiple deliveries, vehicle type and condition, distance traveled, courier quality/rating) most influence delivery speed?

3. Segmentation & Prioritization
Which operational segments (city type, day, peak hour) exhibit the slowest delivery performance, and how should improvements be prioritized?

📊 Dataset

Source: Kaggle

Rows: 45.584

Columns: 20

🛠️ Tools

• Python

• Pandas

• NumPy

• Matplotlib

• Seaborn

• Power BI

📈 Analysis

• Data Cleaning

• Exploratory Data Analysis

• Correlation Analysis

• Feature Analysis

• Business Insights

📊 Dashboard

<img width="1010" height="709" alt="image" src="https://github.com/user-attachments/assets/36aa3514-9353-49a8-8b7e-a1042558e464" />

<img width="1008" height="708" alt="image" src="https://github.com/user-attachments/assets/d20f63ab-2dc4-460d-a256-f64fb86e69ff" />

🔑 Key Findings

• Festival increases delivery time by 75.5%

• Multiple deliveries increase delivery time by 51.2%

• Heavy traffic increases delivery time by 45.4%

• Courier rating has a moderate negative correlation (r = -0.33)

• Distance has a moderate positive correlation (r = 0.32)

💡 Business Recommendations

• Optimize courier allocation during festivals.

• Limit multiple deliveries during peak hours.

• Improve route optimization based on traffic conditions.

• Prioritize experienced couriers for high-demand periods.
