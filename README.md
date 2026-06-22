

---

# <center> **Retail Sales Analysis Using Python: Customer Behavior and Business Insights**  </center>

---
## **Executive Summary**

### This project analyzes retail sales transactions across multiple regions, product categories, and customer segments to identify key drivers of sales performance, profitability, and customer behavior.

### The analysis reveals that the West region is the strongest-performing market in terms of sales, profit, and customer satisfaction. Clothing emerged as the most profitable product category, while Regular customers contributed the highest revenue. Additionally, quantity sold demonstrated a strong positive relationship with sales performance.

### The findings provide actionable business insights that can support strategic decision-making related to customer retention, inventory planning, regional expansion, and revenue growth.

## **Business Problem**

### A retail company operating across multiple regions wants to analyze its sales performance, customer behavior, profitability, and product trends using data analytics techniques. The company collects transactional information such as sales amount, profit, quantity sold, customer ratings, payment methods, and discount percentages.

### Management wants to identify high-performing regions, understand customer preferences, evaluate profitability across products, and analyze how discounts affect business performance. The challenge is to transform raw transactional data into meaningful insights that support strategic business decisions and improve overall performance.

## **Project Introduction**

### Retail businesses generate large volumes of transactional data every day through customer purchases across different regions, products, and sales channels. Hidden within this data are valuable insights that can help organizations understand customer preferences, improve profitability, optimize product strategies, and support better business decisions.

### In this project, a retail company operating across multiple regions aims to analyze its sales performance and understand key factors influencing business growth. The company collects information related to sales transactions, customer ratings, product categories, discounts, payment methods, quantity sold, and profits. However, collecting data alone is not enough—business value comes from converting that raw information into actionable insights.

### The purpose of this analysis is to examine customer purchasing behavior, identify top-performing regions and products, evaluate profitability patterns, and understand how factors such as discounts and payment preferences affect overall business performance. Through data cleaning, exploratory data analysis (EDA), and visualization techniques, this project seeks to uncover meaningful trends and patterns within the dataset.

### By using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, this analysis will transform raw transactional data into business-focused insights that can support strategic decision-making. The findings from this project can help management identify growth opportunities, improve operational efficiency, and make more informed decisions regarding sales and customer strategies.

### This project is not limited to understanding what happened in the sales data, but also focuses on exploring why it happened and identifying opportunities for future improvement.

## **Project Objectives**

* ### Perform data cleaning and preprocessing to improve data quality
* ### Analyze sales performance across different regions and product categories
* ### Identify customer purchasing behavior and revenue patterns
* ### Study the impact of discounts on profitability
* ### Examine customer preferences through payment methods and ratings
* ### Generate meaningful business insights using exploratory data analysis (EDA)
* ### Create visualizations and dashboards for data-driven decision making

## **Dataset Description**

| Column Name | Description |
|-------------|-------------|
| Order_ID | Unique transaction identifier |
| Order_Date | Date of purchase |
| Region | Customer region |
| Category | Product category |
| Product | Product name |
| Customer_Type | Customer segment |
| Quantity | Units purchased |
| Unit_Price | Price per unit |
| Discount_Percent | Discount applied |
| Final_Sales | Final revenue generated |
| Profit | Profit earned |
| Payment_Mode | Payment method |
| Customer_Rating | Customer satisfaction rating |

### This dataset contains transactional retail sales data collected from multiple regions. It includes information related to customer purchases, product categories, sales values, profits, discounts, payment methods, customer ratings, and quantity sold.

### The dataset consists of approximately 200 records and 13 features representing various aspects of retail transactions. The data will be used to perform exploratory analysis and uncover trends, patterns, and business insights.


# **Business Performance Overview (KPIs)**

### The dataset contains 200 retail transactions across multiple regions, product categories, and customer segments. The following key performance indicators (KPIs) provide a high-level summary of overall business performance.

| KPI                     |      Value |
| ----------------------- | ---------: |
| Total Sales             | ₹2,804,583 |
| Total Profit            |   ₹446,502 |
| Total Orders            |        200 |
| Average Order Value     | ₹14,022.92 |
| Average Customer Rating |   2.92 / 5 |
| Profit Margin           |     15.92% |
| Revenue Per Order       |    14022.91|

## KPI Insights
### The business generated total revenue of ₹2.80 million from 200 transactions.
### Total profit amounted to ₹446.5 thousand, resulting in a healthy profit margin of 15.92%.
### The average order value of ₹14,022.92 indicates relatively high-value transactions.
### The average customer rating of 2.92/5 suggests opportunities to improve customer satisfaction and overall shopping experience.
### The combination of strong sales and positive profit margins indicates that the business is operating profitably while maintaining growth potential.

### These KPIs provide a high-level overview of the business performance and serve as the foundation for deeper exploratory analysis.


## **Project Workflow**

### 1. Data Collection
### 2. Data Cleaning
### 3. Data Quality Assessment
### 4. Exploratory Data Analysis
### 5. Visualization
### 6. Business Insights
### 7. Dashboard Creation
### 8. Recommendations



## **Methodology**

### The project follows a structured data analytics approach to convert raw sales data into actionable insights. The methodology includes:

### 1. Data Collection – Importing the retail sales dataset.
### 2. Data Cleaning – Handling missing values, duplicates, and incorrect data types.
### 3. Data Quality Assessment – Evaluating data consistency and reliability.
### 4. Exploratory Data Analysis (EDA) – Understanding patterns and relationships within the data.
### 5. Visualization – Creating charts and graphical representations.
### 6. Business Insight Generation – Identifying trends and interpreting findings.
### 7. Dashboard Development – Building an interactive dashboard for reporting.


## **Data Quality Findings**

### After performing an initial data audit on the retail sales dataset, several observations were identified regarding data quality and structure.

### - The dataset contains 200 rows and 13 columns, providing transactional information related to sales, products, customers, and profitability.

### - No missing values were found across any columns, indicating that the dataset is complete and does not require missing-value treatment.

### - Duplicate value analysis showed zero duplicate records, suggesting that each transaction is unique and data consistency is maintained.

### - Several categorical variables contain a limited number of unique values:
   - Region: 4 unique values
   - Category: 4 unique values
   - Customer Type: 3 unique values
   - Payment Mode: 4 unique values
   - Customer Rating: 5 unique values

### - These variables are suitable for categorical analysis and visualizations such as count plots, bar charts, and comparative analysis.

### Overall, the dataset appears clean and structured, making it suitable for exploratory data analysis and business insight generation.

# Data Quality Assessment

### A comprehensive data quality assessment was performed before conducting the analysis.

# Data Quality Summary

| Check             | Result |
| ----------------- | ------ |
| Total Records     | 200    |
| Total Features    | 13     |
| Missing Values    | 0      |
| Duplicate Records | 0      |

## Key Findings

* No missing values were identified across any variables.
* No duplicate transaction records were found.
* The dataset contains a combination of categorical, numerical, and datetime variables suitable for exploratory analysis.
* The Order_Date field was available in datetime format, enabling time-based trend analysis.
* Overall, the dataset demonstrated a high level of data integrity and was considered suitable for business analysis.

---

# Key Business Questions

### The analysis was conducted to answer the following business questions:

1. Which region generated the highest total sales?
2. Which product category has the highest average profit?
3. What is the relationship between discount percentage and profit?
4. Which payment mode is used most frequently by customers?
5. Which customer type contributes the highest revenue?
6. Which products have the highest and lowest sales?
7. How do customer ratings vary across product categories?
8. What are the monthly sales trends over time?
9. Which region has the highest average customer rating?
10. Is there a relationship between quantity sold and final sales amount?

---

# Strategic Business Insights

## Regional Performance

* ### The West region emerged as the strongest market, generating the highest sales, profit, and customer satisfaction ratings.
* ### The North region consistently underperformed across multiple performance indicators.

## Product Performance

* ### Clothing generated the highest average profit and achieved the highest customer satisfaction score.
* ### Shoes and Mobile products were the primary revenue drivers.

## Customer Behavior

* ### Regular customers contributed the highest overall revenue.
* ### Customers demonstrated a strong preference for digital payment methods, particularly Debit Cards and UPI.

## Sales Trends

* ### March recorded the highest sales performance during the analysis period.
* ### Monthly sales exhibited noticeable fluctuations, suggesting potential seasonal influences.

## Statistical Insights

* ### Discount Percentage and Profit showed a weak negative relationship (Correlation = -0.139).
* ### Quantity Sold and Final Sales exhibited a moderately strong positive relationship (Correlation = 0.688).

---

## Business Recommendations

1. Increase investment in the West region to maximize revenue and profitability.
2. Expand and promote the Clothing category due to its strong profitability and customer satisfaction performance.
3. Improve customer experience initiatives within the North region.
4. Strengthen loyalty programs targeting Regular customers.
5. Continue supporting and optimizing digital payment infrastructure.
6. Prioritize inventory planning for high-performing products such as Shoes and Mobile.
7. Analyze the factors that contributed to March's strong sales performance and replicate successful strategies.
8. Implement quantity-based promotions and bundle offers to encourage larger purchases.

---

# Dashboard and Visualizations

## Total Sales by Region
![alt text](image.png)

## Total Profit by Region
![alt text](image-1.png)

## Monthly Sales Trend
![alt text](image-2.png)

## Top Products by sales
![alt text](image-3.png)

## Project Structure

```text
Retail_Sales_Analysis/
│
├── data/
│   └── business_sales_dataset.xlsx
│
├── notebooks/
│   └── Retail_Sales_Analysis.ipynb
│
├── visuals/
│
├── reports/
│
├── dashboard/
│
├── README.md
│
└── requirements.txt
```

---

# Technologies Used
## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* OpenPyXL
* Jupyter Notebook

## Tools

* Visual Studio Code
* GitHub

---

# Dashboard / Visualizations

The project includes visualizations covering:

* Regional Sales Performance
* Regional Profitability Analysis
* Category Profit Analysis
* Customer Revenue Analysis
* Product Performance Analysis
* Monthly Sales Trends
* Customer Rating Analysis
* Correlation Analysis

Dashboard screenshots and visual outputs can be found in the `visuals/` folder.

---

# Conclusion

### This project demonstrates the application of Python-based data analytics techniques to evaluate retail business performance. Through exploratory data analysis, feature engineering, and statistical analysis, meaningful insights were generated regarding customer behavior, profitability, sales trends, and operational performance.

### The findings support data-driven decision-making and provide actionable recommendations that can help improve profitability, customer satisfaction, and long-term business growth.
