# Target Sales Company - Data Analysis Capstone Project

## **Overview**
As a Data Analyst at Target Sales Company, the primary responsibility is to analyze the company's comprehensive dataset and extract actionable insights to drive strategic decision-making. This project is designed to showcase expertise in advanced SQL queries, data visualization using Power BI/Tableau, and predictive analytics with Python. 

---

## **Dataset**
The dataset contains information on orders, customers, products, regions, and operational metrics. You can download it [here](https://drive.google.com/file/d/1ePnRbauLEyaJMQEgH0GqvL49nReeeUVW/view).

---

## **Phases**

### **Phase 1: SQL Analysis – Advanced Queries**

**Objective:**
Perform in-depth data analysis using advanced MySQL queries to extract actionable insights regarding sales performance, customer behavior, operational efficiency, and time trends.

#### **Tasks and Questions:**
1. **Sales Performance Analysis:**
   - Write a query to calculate total sales revenue per category, sub-category, and region.
   - Identify the top 5 best-selling products by both sales revenue and quantity sold.

2. **Customer Insights:**
   - Find the most loyal customers by calculating their purchase frequency and total spend.
   - Identify customers with the highest Average Order Value (AOV).

3. **Operational Efficiency:**
   - Analyze delivery performance by calculating the average delivery time by region.
   - Identify regions or products with the highest canceled rates.

4. **Date and Time Analytics:**
   - Write a query to find the monthly sales trend for the last two years.
   - Analyze the seasonality of sales to identify peak months.

5. **Advanced SQL Queries:**
   - Use window functions to rank products based on their sales within each category.
   - Calculate month-to-date (MTD) and year-to-date (YTD) sales metrics.

**Resources:**
Use the [CSV to SQL Script](https://github.com/Ayushi0214/SQL-Python-Ecommerce-Project/blob/main/csv_to_sql.py) to upload data to SQL.

---

### **Phase 2: Data Visualization – Power BI or Tableau**

**Objective:**
Create an interactive dashboard to visualize key insights derived from SQL analysis.

#### **Key Metrics to Visualize:**
1. **Sales Performance:**
   - Total Sales Revenue: Overall revenue generated.
   - Average Order Value (AOV): Average revenue per order.
   - Sales by Category and Sub-Category: Revenue breakdown by product categories.
   - Top-Selling Products: Display the top 5 products by sales revenue.

2. **Customer Insights:**
   - Customer Lifetime Value (CLV): Total revenue generated per customer.
   - Top 10 Loyal Customers: Customers with the highest purchase frequency and spend.
   - Customer Segments: Categorize customers based on purchasing behavior (e.g., high spenders, one-time buyers).

3. **Regional Analysis:**
   - Revenue by Region: Comparison of sales by region.
   - Return Rates by Region: Percentage of orders returned per region.
   - Average Delivery Time by Region: Assess operational performance.

4. **Operational Metrics:**
   - Delivery Time Analysis: Average, minimum, and maximum delivery times.
   - Product Return Rates: Percentage of returned products across categories.

5. **Time Trends:**
   - Monthly Sales Trends: Visualization of revenue trends over time.
   - Seasonality Analysis: Highlight peak sales periods (e.g., festive months).

---

### **Phase 3: Predictive Analytics – Python for Forecasting and Machine Learning (Optional)**

**Objective:**
Use Python to forecast sales, segment customers, and build predictive models to enhance decision-making.

#### **Key Tasks:**
1. **Sales Prediction:**
   - Use linear regression to predict monthly sales for the next 12 months.
   - Identify key factors influencing sales trends.

2. **Customer Segmentation:**
   - Perform RFM Analysis (Recency, Frequency, Monetary) and use clustering techniques to classify customers.
   - Label segments (e.g., Loyal Customers, Discount Seekers).

3. **Predicting Product Returns:**
   - Build a logistic regression model to predict the likelihood of a product being returned.

4. **Cross-Sell/Upsell Opportunities:**
   - Use correlation analysis to identify product bundling opportunities.

---

## **Deliverables**

### 1. **SQL Queries:**
- A comprehensive set of advanced SQL queries addressing the tasks in Phase 1, documented in a presentation format.

### 2. **Interactive Dashboard:**
- A visually rich dashboard in Power BI/Tableau, showcasing key metrics with supporting screenshots.

### 3. **Python Code and Models:**
- Forecasted sales data for the next 12 months.
- Segmented customer groups based on clustering.
- Predictive model for identifying high-return products.
- Recommendations for cross-sell/upsell opportunities.

### 4. **Insights Report:**
- A summarized report of findings and actionable recommendations for stakeholders.

---

## **Technology Stack**
- **SQL:** MySQL, Advanced Queries
- **Visualization:** Power BI, Tableau
- **Programming:** Python (pandas, sklearn, matplotlib)

---

## **How to Run**
1. **Phase 1:**
   - Use the provided [script](https://github.com/Ayushi0214/SQL-Python-Ecommerce-Project/blob/main/csv_to_sql.py) to upload the dataset into SQL.
   - Execute SQL queries provided in the repository.

2. **Phase 2:**
   - Load SQL query outputs into Power BI/Tableau.
   - Build dashboards based on the outlined tasks.

3. **Phase 3 (Optional):**
   - Run Python scripts for predictive analytics in Jupyter Notebook or an IDE.
   - Ensure required libraries are installed.

---

## **Contact**
For questions or collaboration opportunities, reach out at [hardikjain0206@gmail.com].
