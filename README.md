# OnlineRetailSaleDataAnalytics
## Overview
This project involves a comprehensive analysis of an online retail dataset containing over 541,000 transactions. The goal is to extract valuable insights related to sales, customer behavior, and product performance, which are crucial for strategic decision-making in the retail industry.

![Project Overview](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*4gzoE-abDTiq16h2T4QJXQ.png)

## Dataset
The dataset consists of the following columns:
- **InvoiceNo**: Unique identifier for each transaction
- **StockCode**: Unique identifier for each product
- **Description**: Description of the product
- **Quantity**: Quantity of products sold or returned
- **InvoiceDate**: Date and time of the transaction
- **UnitPrice**: Price per unit of the product
- **CustomerID**: Unique identifier for the customer
- **Country**: Country where the transaction occurred

## Project Steps

### 1. Initial Analysis
- Loaded the dataset into a Pandas DataFrame and performed initial exploration.
- Conducted null value analysis to identify missing data.

### 2. Data Cleaning
- Handled null values in the **Description** and **CustomerID** fields.
- Assigned 'Guest' to missing CustomerIDs and transformed entries accordingly.

### 3. Product Categorization
- Utilized Hugging Face's zero-shot classification model to categorize products based on descriptions without needing a predefined training dataset.

### 4. Google BigQuery Integration
- Uploaded the dataset to Google Cloud Platform for scalable analysis.
- Executed SQL queries to derive key metrics, including discount items, product categories, customer metrics, and revenue trends over time.

### 5. Visualization
- Created an interactive Tableau dashboard showcasing key performance indicators (KPIs), top-performing countries and categories, and monthly revenue trends.

## Key Insights
- Identified high-revenue products and their associated categories.
- Pinpointed peak revenue times for targeted marketing efforts.
- Analyzed customer metrics across different countries.

## Tools Used
- Python (Pandas)
- Jupyter Notebook
- Google Colab
- Hugging Face Transformers
- Google BigQuery
- Tableau [Dashboard](https://public.tableau.com/app/profile/vikas.marwadi/viz/OnlineRetailSales-Dashboard/Dashboard2)

## Conclusion
This project demonstrates the integration of natural language processing (NLP), cloud-based analytics, and SQL to derive meaningful insights from raw retail data. The findings can significantly enhance operational efficiency and strategic decision-making in retail.
