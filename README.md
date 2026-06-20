# Netflix User Base — Exploratory Data Analysis 📊

An exploratory data analysis (EDA) of a Netflix user base dataset, using Python to uncover patterns in user demographics, device usage, subscription types, and revenue across different countries.

📌 Overview
This project takes a raw dataset of Netflix users and explores it step by step — cleaning the data, converting data types, engineering new columns, and building visualizations to answer questions like:

- Which countries have the most users?
- How is revenue distributed across countries?
- What devices do users watch on most?
- How are users split by gender and subscription type?

🛠️ Tools & Libraries
- Python
- Pandas — data cleaning and manipulation
- Matplotlib & Seaborn — data visualization
- Jupyter Notebook — analysis environment

🔍 Analysis Steps
Data loading — imported the dataset with Pandas
Data cleaning — handled missing values and corrected data types
Feature engineering — converted dates with to_datetime and derived new columns such as subscription duration in months
Exploratory analysis — used value_counts() and pivot_table() to summarize the data
Visualization — created bar charts to display key breakdowns

📈 Key Visualizations
- Users per Country — number of users in each country
- Revenue by Country — total revenue contribution per country
- Users by Device — distribution of streaming devices
- Users by Gender — gender split across the user base
- Users by Subscription Type — popularity of each plan tier

📝 Key Takeaways
This project demonstrates a full EDA workflow — from raw data to clean, insightful visualizations — and practices core data analytics skills including data cleaning, feature engineering, grouping/aggregation, and visualization.
