# My-First-Project-Documentation
This is where i started my portfolio building while taking Data Analysis class with incubator                                                                            

I have learnt a number of things ranging from Ms Excel and SQL and now to my portfoilio building

## ProjecTopic: E Commerce Salea Analysis

### Project Overview

E-commerce sales analysis is a critical process for businesses that operate online stores. It involves examining various data points, such as revenue trends, customer purchasing behavior, product performance, and marketing effectiveness. By analyzing this data, businesses can optimize their strategies, improve customer experience, and increase profitability.

### Data Source
The dataset for this analysis comes from online e-commerce platforms. Sources may include:
- Kaggle: Open-source datasets on sales transactions.
- Google Trends: Tracking consumer interest in products.
- Web Scraping: Extracting structured sales data from online stores (ensure ethical compliance)

### Tools Used
- Ms Excel for data cleaning [Download Here](https://wwww.microsoft.com)
     - For data collection
     - For data cleaning
       1. data manipulation
       2. data munching
- SQL Server for querying and Analysis
- Power Bi for creating report [Dowload Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
- Ms Powerpoint for presentation

### Data Preparation & Cleaning
Properly structured data ensures accurate analysis. Steps include:
1. Handling Missing Data
2. Data loading and inspection
3. Removing Duplicates 
4. Data cldaning and  Formats 

### Exploratory Data Analysis (EDA)
EDA helps us understand the dataset before performing deeper analysis. Key steps include:
- What is the overall sales trend
- Which is product are top sellers
- What are the products on the peak sales?

### Data Analysis & Code Used
Retrieve total sales per month
***  
      SQL
      SELECT DATE_TRUNC('month', order_date) AS sales_month, 
       SUM(order_amount) AS total_sales
      FROM sales_data
      GROUP BY sales_month
      ORDER BY sales_month;
***
