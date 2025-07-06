
[Jump to PDC](###Data-Preparation-&-Cleaning)

# My-First-Project-Documentation
This is where i started my portfolio building while taking Data Analysis class with incubator                                                                            

I have learnt a number of things ranging from Ms Excel and SQL and now to my portfolio building

## ProjecTopic: Amazon Product Review Analysis and Kultra Mega Stores Inventory Analysis

### Project 1 Overview of  Amazon Product Review Analysis [SEE PROJECT](https://docs.google.com/spreadsheets/d/1EUs3A12lauBiQOc4uDmswa_YXKLJB05A/edit?usp=sharing&ouid=113106892741220617192&rtpof=true&sd=true)

As a Junior Data Analyst at RetailTech Insights, a company that provides analytics solutions to Amazon sellers, I was tasked with analyzing product and customer review data. The goal was to extract actionable insights that support:
- Product improvement
- Customer engagement strategies
- Marketing optimization


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

### Project 2 Overview of Kultra Mega Stores Inventory Analysis [SEE PROJECT](https://drive.google.com/file/d/1KmNoXKgkNiFEEuag1adMWJ7J4ACW6FC0/view?usp=sharing)

As a Business Intelligence Analyst working with the Abuja Division of Kultra Mega Stores (KMS), I was responsible for analyzing order data between 2009–2012. KMS specializes in office supplies and furniture, catering to individuals, small retail(ers, and corporate clients across Nigeria.
Using SQL, I was tasked with uncovering patterns in:
- Customer behavior
- Product performance
- Regional profitability
- Operational cost efficiency
This analysis was part of the DSA Data Analysis program, focusing on real-world business use cases.

### Tools Used
- SQL Server Management Studio (SSMS)
- For querying and in-depth analysis of structured data
- Commonly used SQL operations:
- GROUP BY, ORDER BY, WHERE, JOIN, subqueries
- Aggregation: SUM(), COUNT(), AVG()
- SQL Server for querying and Analysis

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

### Key Questions Solved
- Which product category generated the highest revenue?
- What regions lead or lag in sales?
- Who are the most valuable customers by segment?
- Are shipping costs aligned with order priority levels?
- How can underperforming customers be re-engaged?

 ### Insights Delivered
- Strategic recommendations for low-performing customers
- Optimization opportunities in shipping modes and order urgency
- Target product categories for profitability uplift

### Data Analysis & Code Used
Retrieve total sales per month
***  
      SQL
      -- Example: Highest Selling Product Category
     SELECT TOP 1 [Product_Category],
    SUM(Sales) AS TotalSales FROM [dbo].[KMS Sql Case Study]
     GROUP BY [Product_Category]
     ORDER BY TotalSales DESC;
***

## Analysis
![chart](https://github.com/user-attachments/assets/78550d20-81f7-40d4-963a-ed266f20546a)(C:\Users\LENOVO\OneDrive\Desktop)

### Conclusion
- Excel was powerful for visualizing trends in product reviews and customer feedback on Amazon.
- SQL helped answer important business questions for KMS based on real sales data.
- I used cleaning, exploration, and querying skills to turn raw data into useful insights.
- The findings can help improve marketing, reduce costs, and grow sales.
