# Customer Shopping Behavior – Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow** using Python, SQL, and Power BI. It covers data ingestion, exploratory data analysis (EDA), data cleaning, database querying, and business-focused visualization. The goal is to transform raw customer shopping data into clear, actionable insights through analysis, a dashboard, and a presentation.

---

## Dataset

* **Source:** Customer shopping behavior dataset (CSV)
* **Description:** Contains customer demographics, purchase details, and transaction-level attributes used to analyze buying patterns and trends.
* **Format:** `.csv`

Key columns include customer attributes, purchase frequency, categories, spending metrics, and time-based fields.

---

## Tools & Technologies

* **Python:** Data loading, EDA, and data cleaning (Pandas, NumPy, Matplotlib/Seaborn)
* **SQL (PostgreSQL):** Data storage and analytical queries
* **Power BI:** Interactive dashboard and visual reporting
* **Gamma:** Presentation (PPT-style report)
* **Jupyter Notebook:** Analysis and documentation

---

## Project Workflow

1. **Data Loading (Python)**

   * Load the raw CSV dataset into a Pandas DataFrame
   * Perform initial inspections (shape, schema, missing values)

2. **Exploratory Data Analysis (EDA)**

   * Analyze distributions, trends, and correlations
   * Identify key metrics such as customer segments, spending patterns, and popular categories

3. **Data Cleaning & Preparation**

   * Handle missing and inconsistent values
   * Standardize column formats and data types
   * Prepare the dataset for database ingestion

4. **SQL Analysis (PostgreSQL)**

   * Load cleaned data into a PostgreSQL database
   * Write analytical SQL queries to answer business questions
   * Validate Python insights using SQL-based aggregation

5. **Visualization & Reporting**

   * Build an interactive **Power BI dashboard** for stakeholders
   * Create a concise presentation in **Gamma** summarizing insights and recommendations

---

## Dashboard

The Power BI dashboard highlights:

* Customer segmentation and demographics
* Purchase frequency and spending behavior
* Category-level performance
* Key KPIs and trends

The dashboard is designed to be **interactive, intuitive, and decision-focused**.

---

## Results & Key Insights

* Identified high-value customer segments and spending patterns
* Discovered top-performing product categories
* Highlighted trends that can inform marketing and retention strategies
* Demonstrated consistency between Python and SQL-based analysis

---

## How to Run the Project

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. **Set up Python environment**

   ```bash
   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
   ```

3. **Run analysis**

   * Open the Jupyter Notebook
   * Execute cells in order for EDA and data cleaning

4. **PostgreSQL Setup**

   * Create a PostgreSQL database
   * Load the cleaned dataset into tables
   * Run the provided SQL queries

5. **Dashboard & Presentation**

   * Open the Power BI `.pbix` file to explore the dashboard
   * Review the Gamma presentation for a summarized business report

---

## Notes

* This project is structured to reflect **real-world analytics workflows**
* Clear separation between data processing, querying, and reporting
* Suitable as a **portfolio project** for data analyst and data science roles

---

**Author:** Daivik Patel
**Focus Areas:** Data Analytics | SQL | Python | Power BI
