☕ Coffee Shop Sales Analysis
A data analysis project exploring customer purchases at a coffee shop. The goal is to extract meaningful insights about sales patterns using Python, Pandas, and data visualization libraries.

🔍 Project Objectives
Understand customer behavior by time of day, week, and month

Identify best-selling coffee types and peak hours

Visualize sales trends over time

Create actionable insights for business decisions (e.g., staffing, promotions)

📁 Dataset
The dataset (data.csv) contains:

Column Name	Description
date	Date of transaction
datetime	Timestamp of transaction
cash_type	Payment method (e.g., card, cash)
card	Anonymized card ID (nullable)
money	Transaction value in local currency
coffee_name	Name of the coffee sold

⚙️ Methods and Tools
Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Feature Engineering: Time-based features (hour, weekday, month)

Data Cleaning: Null check, duplicates, datetime parsing

Visualizations:

📊 Bar charts (revenue per coffee type, weekday sales)

📈 Line plots (monthly trend)

🗺️ Heatmap (hourly sales by coffee type)

📦 Box plot (sales time distribution)

📊 Key Insights
Best-selling item: Latte generated the highest total revenue.

Peak hours: Most transactions occurred at 10:00 AM, followed by 11:00 AM and 7:00 PM.

Busy days: Highest sales volume on Saturday and Sunday.

Monthly trend: Sales showed consistent popularity for specific drinks.

📌 Visuals
Total Revenue by Coffee Type


Monthly Sales Trend


Weekly Sales Volume


Hourly Heatmap


📈 Optional ML Extension
You can extend this project by:

Predicting sales volume using regression

Clustering customer behavior by card usage

Detecting outliers or anomalies in sales patterns
