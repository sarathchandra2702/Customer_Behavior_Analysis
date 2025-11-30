# Customer_Behavior_Analysis
A data analytics project showcasing customer behavior analysis using python, SQL and powerBI

Data Analytics Project – End-to-End Analysis Pipeline


📌 Overview

This project demonstrates a complete data analytics workflow—from loading raw data in Python to delivering final business insights through a Power BI dashboard, a written report, and a presentation created using Gamma.
It highlights skills in data cleaning, exploratory data analysis (EDA), SQL querying, dashboard design, and storytelling with data.


📂 Dataset

Name: customer_shopping_behavior

Format: CSV 

Description: 

Total Rows: 3,900

Total Columns: 18

Main Attributes Included:

o	Customer demographics such as age, gender, location, and subscription status

o	Purchase-related information like item bought, product category, amount spent, season, size, and color

o	Behavioral indicators including discount usage, promo codes applied, past purchases, purchase frequency, review ratings, and shipping method

Missing Values: 37 entries are missing in the Review Rating field


🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib/Seaborn)

PostgreSQL + SQL

Power BI

Jupyter Notebook / VS Code

Gamma App (for presentation)

Microsoft Word / Google Docs (for written report)



🔍 Project Steps
1️⃣ Load & Inspect Dataset (Python)

Imported dataset using Pandas

Checked data types, missing values, duplicates

Performed basic EDA to understand structure and distributions

2️⃣ Data Cleaning

Handled missing values

Removed duplicates

Fixed inconsistencies (categories, formats, datatypes)

Created new calculated fields if needed

3️⃣ Exploratory Data Analysis (EDA)

Summary statistics

Trend, distribution, and correlation analysis

Visualization using Matplotlib/Seaborn

Identified key patterns, insights, and anomalies

4️⃣ SQL Analysis in PostgreSQL

Loaded cleaned data into PostgreSQL

Executed SQL queries for deeper analysis

Aggregations

Joins

Window functions

Filtering & segmentation

Exported results for dashboard and reporting

5️⃣ Power BI Dashboard

Connected to cleaned dataset / SQL outputs

Built an interactive dashboard including:

KPIs

Trend charts

Category-wise breakdowns

Slicers for interactivity

Designed a clean, business-friendly layout

6️⃣ Report Creation

Compiled findings, insights, and recommendations

Summarized EDA, SQL results, and dashboard outcomes

7️⃣ Presentation using Gamma

Designed a modern, visual presentation

Included problem statement, methodology, insights, and final takeaways

Tailored slides for a non-technical audience


📈 Key Insights & Results

•	Increase Subscriptions: Market exclusive perks more effectively to encourage customers to subscribe.
•	Enhance Loyalty Programs: Offer rewards to frequent shoppers to transition them into the “Loyal” customer segment.
•	Optimize Discount Strategy: Reassess discount usage to maintain a balance between increased sales and profit margins.
•	Improve Product Positioning: Feature top-rated and best-selling items prominently in marketing campaigns.
•	Implement Targeted Marketing: Direct promotional efforts toward high-spending age groups and customers who prefer express shipping.


▶️ How to Run the Project
Prerequisites

Python 3.x

PostgreSQL installed and running

Power BI Desktop

Required Python libraries:

pip install pandas numpy matplotlib seaborn psycopg2-binary


Steps:

Clone the repository

Open the Jupyter Notebook and run the Python scripts for EDA & cleaning

Import the cleaned dataset into PostgreSQL

Run SQL queries from the /sql folder

Open the Power BI file to explore the dashboard

View the report (/report) and presentation (/presentation) folders
