Sales Funnel Analysis Dashboard – Report
1️⃣ Introduction

The objective of this task is to analyze sales funnel data and create an interactive dashboard that helps understand lead generation and conversion performance. The dashboard was built using Python for data cleaning and Power BI for visualization.

2️⃣ Tools & Technologies Used
Tool	Purpose
Python (Pandas)	Data cleaning & preprocessing
Power BI	Data visualization & dashboard creation
CSV Dataset	Sales Funnel dataset
3️⃣ Dataset Description

The dataset contains information about marketing leads and their conversion status.

Key Columns Used
Lead Source → Where the lead came from
Converted → Whether the lead converted (0 = No, 1 = Yes)
Other funnel attributes

The data was cleaned and prepared before visualization.

4️⃣ Data Cleaning Process (Python)
Steps Performed
Loaded dataset using Pandas.
Handled encoding errors.
Removed null and unwanted values.
Converted data into clean CSV file.
Exported cleaned dataset for Power BI.
Output File

cleaned_funnel_data.csv

This file was used for dashboard creation.

5️⃣ Dashboard Objectives

The dashboard answers the following business questions:

How many leads are generated?
How many leads are converted?
What is the conversion rate?
Which lead sources perform best?
Where do leads drop in the funnel?
6️⃣ Key Metrics Created
KPI Cards
Total Leads Generated
Shows total number of leads.
Total Conversions
Shows number of converted leads.
Conversion Rate %
Formula used:
Conversion Rate = (Total Conversions / Total Leads) * 100
7️⃣ Visualizations Created
📊 1. Conversions by Lead Source (Bar Chart)

Shows which marketing channel generates the most conversions.

Business Insight:
Helps identify high-performing marketing channels.

🔻 2. Lead Funnel Overview (Funnel Chart)

Shows flow from leads → conversions.

Business Insight:
Helps identify drop-off points in the sales funnel.

8️⃣ Filters (Interactive Slicers)

Two slicers were added to make dashboard interactive:

Lead Source Filter
Allows analysis by marketing channel.
Conversion Status Filter
Allows filtering by Converted / Not Converted.

These filters help stakeholders explore the data dynamically.

9️⃣ Dashboard Design Principles Used
Clean layout and alignment
Consistent titles and colors
KPI cards at top for quick insights
Charts placed in center for analysis
Filters placed on side for interaction
🔟 Key Insights

From the dashboard:

Total leads generated can be tracked easily.
Conversion performance is clearly visible.
Best performing lead sources can be identified.
Funnel visualization highlights conversion efficiency.
Dashboard allows interactive exploration using filters.
11️⃣ Conclusion

This project demonstrates how data analytics can be used to analyze marketing funnel performance.
Using Python and Power BI, raw data was transformed into meaningful insights through an interactive dashboard.

The dashboard can help businesses:

Improve marketing strategy
Increase conversion rates
Make data-driven decisions
