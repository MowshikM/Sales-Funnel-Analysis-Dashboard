Marketing Funnel & Conversion Performance Analysis
1️⃣ Objective

The goal of this project is to analyze the marketing funnel performance and understand how leads move from generation to conversion.
The project focuses on identifying key metrics, conversion efficiency, and the effectiveness of different lead sources using an interactive Power BI dashboard.

2️⃣ Tools & Technologies Used
Tool	Purpose
Python (Pandas)	Data cleaning & preprocessing
Power BI	Dashboard & visualization
CSV Dataset	Marketing funnel data
3️⃣ Problem Statement

Businesses generate leads through different marketing channels, but not all leads convert into customers.
The challenge is to:

Track total leads generated
Measure conversion performance
Identify best performing lead sources
Understand conversion efficiency

This project solves the above problems using data analytics.

4️⃣ Data Preparation (Python)

Before creating the dashboard, the dataset was cleaned using Python.

Steps Performed
Imported dataset using Pandas
Fixed encoding errors
Checked missing values
Cleaned inconsistent data
Exported cleaned dataset
Output File

funnel_cleaned.csv

This cleaned file was used inside Power BI.

5️⃣ Key Metrics Created
KPI 1 — Total Leads Generated

Total number of leads available in dataset.

KPI 2 — Total Conversions

Total number of leads that became customers.

KPI 3 — Conversion Rate %

Formula used in Power BI:

Conversion Rate % = (Total Conversions / Total Leads) * 100

This metric shows how effective the marketing funnel is.

6️⃣ Dashboard Visualizations
📊 1. Conversions by Lead Source (Bar Chart)

Shows how many conversions come from each marketing channel.

Purpose:
Helps identify high-performing marketing channels.

Business Value:
Companies can invest more in the best lead sources.

🔻 2. Lead Funnel Overview (Funnel Chart)

Shows the flow from:

Leads → Converted Customers

Purpose:
Visualizes drop-off in the funnel.

Business Value:
Helps improve conversion strategies.

7️⃣ Interactive Filters (Slicers)

To make the dashboard interactive, slicers were added.

Filters Created

1️⃣ Lead Source Filter
Allows filtering by marketing channel.

2️⃣ Conversion Status Filter
Allows filtering by:

Converted
Not Converted

This enables dynamic analysis.

8️⃣ Dashboard Design Approach

Professional dashboard design principles were followed:

KPI cards placed at top for quick overview
Charts placed in center for analysis
Slicers placed on side for filtering
Consistent titles and formatting
Clean and minimal layout
9️⃣ Key Insights

From the dashboard analysis:

Total lead generation can be tracked easily.
Conversion performance is clearly measurable.
Best performing lead sources are identified.
Funnel visualization highlights conversion efficiency.
Interactive filters allow deeper analysis.
🔟 Business Impact

This dashboard helps businesses:

Improve marketing strategy
Optimize lead generation campaigns
Increase conversion rate
Make data-driven decisions
11️⃣ Conclusion

This project demonstrates how marketing funnel data can be transformed into meaningful business insights using Python and Power BI.

The final dashboard provides a clear view of lead generation, conversions, and marketing performance, enabling stakeholders to make informed decisions.
