# e-commerce-retail-analysis

Project Goal:
Analyze transactional retail data to understand sales volume, revenue distribution, and customer purchasing behavior over a short time period.

Dataset:

 - Online Retail dataset (UK transactions)
 - Time range: 3 days
 - ~6,300 rows after filtering and cleaning

Data Source Note:

The original raw dataset was not uploaded to this repository due to GitHub file size limitations (the source file exceeds 25 MB).

The dataset was obtained from an open-source Kaggle repository:
 - https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci


Data Preparation:

 - Filtered by country (United Kingdom)
 - Split InvoiceDate into Date and Time
 - Created time-of-day segments (Morning / Afternoon / Evening)
 - Handled missing CustomerID values without imputation
 - Ensured correct numeric formats for quantity and price

Key Metrics:

 - Total Revenue
 - Number of Unique Invoices
 - Average Order Value (AOV)

# Key Insights:

 - Average Order Value is highest in the morning hours
 - Total revenue peaks during daytime due to higher sales volume
 - High AOV does not necessarily imply higher total revenue
 - Revenue is driven primarily by quantity sold rather than price

Tools Used:

 - Microsoft Excel
 - Pivot Tables
 - Conditional Formatting
 - Calculated Fields
 - Basic business metrics (Revenue, AOV)
