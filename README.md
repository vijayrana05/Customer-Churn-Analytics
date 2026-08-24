# Customer Churn Analytics & Business Intelligence Pipeline

## Project Overview
An end-to-end data analytics pipeline designed to analyze customer churn drivers, calculate key business metrics, and quantify revenue at risk for an OTT subscription platform.

## Tech Stack & Tools
* **Language:** Python, SQL
* **Database:** SQLite
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

## Key Features & Highlights
* **Relational Data Extraction:** Connected Python to SQLite database to ingest multi-table datasets (`db_customer`, `db_subscription`, `db_support`).
* **Data Cleaning & Preprocessing:** Resolved missing values, standardized data types, and applied categorical encoding.
* **Business Metric Engineering:** Calculated critical retention KPIs including Churn Rate, Retention Rate, ARPU (Average Revenue Per User), and Revenue at Risk.
* **Exploratory Visualizations:** Constructed correlation heatmaps and multi-dimensional category plots to isolate high-risk subscriber segments.

## Project Structure
* `churn_analysis.ipynb`: Complete Jupyter Notebook with code, data cleaning steps, and visual outputs.
* `customer_churn.db`: SQLite database file.
* `customer_churn_data_raw.xlsx`: Excel raw data source.
