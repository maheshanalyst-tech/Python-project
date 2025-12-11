# Python-project
Capstone project in python
📊 Marketing Campaign Performance Insights – Capstone Project

This project performs an end-to-end exploratory data analysis (EDA) on a marketing campaign dataset.
It includes descriptive statistics, visualizations, customer segmentation insights, channel effectiveness, and time-based trend analysis to help marketers optimize strategy and improve campaign performance.

📁 Project Structure
📦 Marketing-Campaign-EDA
 ┣ 📜 README.md
 ┣ 📜 marketing_campaign_analysis.ipynb
 ┗ 📜 marketing_campaign.csv

📌 Project Objective

The main goal of this project is to uncover insights from marketing campaign data, including:

Campaign performance analysis

Customer segment behavior

Channel effectiveness

Time-based trends

Geographic insights

These findings help optimize conversion rates, reduce acquisition costs, and improve ROI.

📊 Dataset Overview

The dataset contains 22,029 records and 16 features, including:

Column	Description
Campaign_ID	Unique ID for each campaign
Company	Company running the campaign
Campaign_Type	Email, Social Media, Influencer, etc.
Target_Audience	Demographic group
Duration	Campaign duration
Channel_Used	Platform used (Facebook, Instagram, etc.)
Conversion_Rate	Percentage of conversions
Acquisition_Cost	Cost per customer acquisition
ROI	Return on investment
Location	City/Region
Language	Communication language
Clicks	Number of clicks
Impressions	Number of impressions
Engagement_Score	Engagement level (1–10)
Customer_Segment	Audience segmentation
Date	Campaign launch date

Dataset Source:
https://github.com/ArchanaInsights/Datasets

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

📥 Loading the Dataset
import pandas as pd

csvfile = "https://raw.githubusercontent.com/ArchanaInsights/Datasets/main/marketing_campaign.csv"
df = pd.read_csv(csvfile)

🔍 Key Analysis Performed
1️⃣ Descriptive Analysis

Preview dataset (head())

View structure (info())

Summary statistics (describe())

Count unique values

Category distributions

2️⃣ Exploratory Data Analysis (EDA)
📌 Campaign Performance

Scatter plot: Acquisition Cost vs ROI

Bar chart: Conversion Rate by Channel & Campaign Type

Box plot: Engagement Score across Campaign Types

Average ROI by company

Correlation heatmap: Engagement Score vs Conversion Rate

3️⃣ Customer Segmentation

Target audience distribution

Conversion rate comparison by Language & Customer Segment

Acquisition cost differences across customer groups

Conversion rate across languages

4️⃣ Channel Effectiveness

Engagement Score comparison across channels

ROI distribution by channel (Pie chart)

Clicks vs Impressions scatter plot

5️⃣ Time-Based Trends

Campaign duration distribution

Conversion Rate trends by company

Engagement Score over time

6️⃣ Geographic Analysis

Highest Acquisition Cost by location

Conversion Rate by location & audience segment

ROI proportion by location

📈 Sample Visualizations

✔ Scatter plots
✔ Bar charts
✔ Box plots
✔ Pie charts
✔ Line charts
✔ Heatmaps

All visualizations are created using Matplotlib and Seaborn.

🚀 Key Insights (Summary)

Some channels produce higher engagement but lower ROI, and vice-versa.

Demographics and language influence Conversion Rates significantly.

Acquisition Cost varies widely across locations and segments.

Strong correlation exists between engagement and conversion for certain segments.

Time-based trends reveal campaigns that improve or decline over time.

📌 Future Enhancements

Add machine learning models to predict ROI or Conversion Rate

Build an interactive dashboard using Plotly or Power BI

Automate report generation using scripts

Apply clustering techniques for deeper segmentation
