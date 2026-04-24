# E-Commerce Data Analysis Project
This peoject focuses on analyzing e-commerce dataset to derive actionable business insights using **Python** ,**Pandas** and **matplotlib**. The analysis covers data cleaning, sales trends, product performance and customer behavior metrics.
l performed data analysis steps:
### 1. Data Cleaning & Transforemation
- **Handling Datetime**: Converted raw date strings into proper `datetime` objects to allow for time-series analysis.
-  **Text Standartization**: Cleaned product descriptions by converting them to uppercase and removing extra whitespaces to merge duplicates.
-  **Filterization Noise**: Identified and removed non-product entries to accurate analysis.
### 2. Sales Trend Analysis
- **Monthly Revenue**: Extracted months from invoice dates and visualized the total revenue trend using line charts.
- **Top Selling Products**: Identified the highest-grossing products by calculating total revenue per item and visualizing them with bar charts.
### 3. Customer & Order Metrics
- **Average Order Value (Aov)**: Calculated the Aov by grouping sales by `InvoiceNo` and determining the mean transaction value.
- -**Customer Segmentation**: Aggregated data at the customer level to track total spending and frequency of pruchases (Customer Loyalty)
- **Return Analysis**: Isolated and analyzed returned items (indicated by negative quantities) to identify the most frequently returned products.
- ### 4. Data Visualization
- Utilized  **Matplotlib** to create clear and professional visualizations, including:
- Monthly Sales Trend (Line Charts)
- Top Selling Products (Bar Charts with rotated labels for readability)
- Return Distribution Analysis
## Tools Used
- **Python**
- **Pandas**: For data maniplutaion and cleaning.
- **Matplotlib**: For Data visualization:
- **Jupyter Notebook**: Development environment.

## Insights 
- Cleaned the dataset to focus on real transactions, removing administration notes.
- Visualized peak sales periods to understand seasonal trends.
- Calculated key performance indicators (KPIs) like AOV to measure business health.
----
## Storytelling 
