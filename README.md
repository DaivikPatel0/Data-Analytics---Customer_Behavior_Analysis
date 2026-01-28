# Data-Analytics---Customer_Behavior_Analysis

Overview
This project provides an end-to-end data analytics solution designed to uncover key insights into customer spending patterns, demographics, and loyalty. By processing a dataset of 3,900 transactions, the project demonstrates a full data pipeline: from raw data cleaning in Python and advanced querying in PostgreSQL to visual storytelling in Power BI and automated reporting.

The primary goal is to help businesses understand which factors (such as discounts, shipping types, or membership status) most significantly drive revenue and customer retention.

Dataset
The analysis is based on the Customer Shopping Behavior Dataset, which includes:

Total Records: 3,900 rows

Key Features: Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, and Previous Purchases.

Target Insights: Identifying high-value segments and optimizing discount strategies.

Tools & Technologies
Language: Python (Pandas, SQLAlchemy, Matplotlib/Seaborn)

Database: PostgreSQL (Relational Data Modeling & Complex Querying)

Visualization: Power BI (Interactive Dashboards)

Documentation: Gamma AI (Professional Slide Deck Generation)

Environment: Jupyter Notebook, VS Code, pgAdmin 4

Project Steps
1. Data Preparation & EDA (Python)
Loaded the raw CSV using Pandas.

Handled missing values (notably in the Review Rating column).

Performed Exploratory Data Analysis (EDA) to identify outliers and understand distribution across age and gender.

Exported the cleaned data to a PostgreSQL server using SQLAlchemy for structured querying.

2. SQL Analysis (PostgreSQL)
Authored complex queries to answer critical business questions, including:

Revenue Segmentation: Comparing total spend by gender and subscription status.

Product Performance: Identifying the top 5 products with the highest average ratings.

Discount Impact: Calculating the percentage of purchases made with discounts per product using conditional aggregation.

Loyalty Metrics: Segmenting customers into 'New', 'Returning', and 'Loyal' based on previous purchase history.

3. Interactive Dashboard (Power BI)
Developed a multi-view dashboard to visualize KPIs:

Sales Overview: Total Revenue, Average Purchase Amount, and Total Customers.

Demographics: Revenue breakdown by Age Group (Young Adult, Middle-aged, Senior).

Category Analysis: Identifying 'Clothing' and 'Accessories' as top revenue drivers.

Behavioral Trends: Correlation between subscription status and purchase frequency.

4. Professional Reporting (Gamma & PDF)
Synthesized findings into a professional report.

Used Gamma AI to generate a recruiter-friendly presentation deck highlighting business recommendations and technical methodology.

Key Results & Insights
High-Value Segments: "Young Adults" contribute the highest total revenue ($62k+), followed closely by "Middle-aged" customers.

Subscription Impact: While subscribers represent only 27% of the customer base, they show higher consistency in repeat purchases.

Category Leaders: Clothing remains the dominant category, while Footwear shows the highest potential for growth through targeted discounts.

Shipping Preference: Standard shipping is the most utilized, but Express shipping users tend to have a higher average order value (AOV).

How to Run This Project
Prerequisites
Python 3.x

PostgreSQL Server

Power BI Desktop

Setup
Database: * Create a database named customer_behavior in PostgreSQL.

Run the schema/table creation steps found in Customer_Behavior_Analysis.sql.

Python Environment:

Install dependencies: pip install pandas sqlalchemy psycopg2-binary.

Open Customer_Shopping_Behavior_Analysis.ipynb and update the database credentials (username/password) to match your local setup.

Run all cells to clean data and upload it to SQL.

Visualization:

Open customer_behavior_dashboard.pbix in Power BI.

(Optional) Reconnect the data source to your local PostgreSQL instance.
