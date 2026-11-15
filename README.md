# Devixo-Solution-Data-Science-Task-4
# Business Analytics Project – Global Superstore

**Internship Project | Devixo Solutions**

## 📌 Project Overview

This project focuses on analyzing the Global Superstore dataset to understand business performance, identify sales and profitability trends, study customer behaviour, and generate actionable business recommendations.

The project uses **Python for data cleaning and exploratory data analysis (EDA)** and **Power BI for interactive business intelligence dashboards**.

## 🎯 Project Objectives

- Clean and preprocess the raw business dataset.
- Analyze sales, profit, customers, products, and regional performance.
- Calculate important business KPIs.
- Identify trends, patterns, and potential business problems.
- Develop interactive Power BI dashboards.
- Provide data-driven recommendations to improve business performance.

## 📊 Dataset Information

The Global Superstore dataset contains transaction-level information about sales, customers, products, shipping, and business regions.

| Dataset Detail | Value |
|---|---:|
| Total Rows | 51,290 |
| Total Columns | 30 |
| Duplicate Rows After Cleaning | 0 |
| Missing Values After Cleaning | 0 |

**Important columns include:**

- Order ID, Order Date, Ship Date
- Customer ID, Customer Name, Segment
- Country, City, State, Region, Market
- Product ID, Category, Sub-Category, Product Name
- Sales, Quantity, Discount, Profit, Shipping Cost

### Feature Engineering

The following additional features were created:

- Shipping Days
- Order Year
- Order Month
- Month Name
- Year-Month
- Profit Margin

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Jupyter Notebook | Writing and executing Python code |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Power BI | Interactive dashboards |
| DAX | KPI and business measure calculations |
| GitHub | Project documentation and portfolio |

## 🧹 Data Cleaning and Preprocessing

The following operations were performed:

1. Loaded and inspected the raw dataset.
2. Checked data types and dataset structure.
3. Identified and handled missing values.
4. Checked and removed duplicate records.
5. Converted date columns into datetime format.
6. Corrected data types where required.
7. Created additional analytical features.
8. Checked the cleaned dataset.

**Final cleaning results:**
- Final dataset shape: 51,290 rows × 30 columns.
- Missing values: 0.
- Duplicate records: 0.

## 📈 Exploratory Data Analysis (EDA)

The project includes the following analyses:

- Business Overview and KPI Analysis
- Monthly and Yearly Sales Trends
- Category and Sub-Category Analysis
- Regional and Market Performance
- Customer Analysis
- Customer Segmentation
- Shipping Performance Analysis
- Discount Analysis
- Order Priority Analysis
- Statistical Summary
- Outlier Detection Using the IQR Method
- Transaction-Level Analysis
- Correlation Analysis

## 📌 Key Business KPIs

| KPI | Result |
|---|---:|
| Total Sales | 12,642,501.91 |
| Total Profit | 1,467,457.29 |
| Total Quantity Sold | 178,312 |
| Total Orders | 25,035 |
| Total Customers | 1,590 |
| Unique Product IDs | 10,292 |
| Average Order Value | 504.99 |
| Overall Profit Margin | 11.61% |

*Note: The dataset's currency unit is not specified here, so values are presented without a currency symbol.*

## 🔍 Key Insights

1. **Sales Performance:** The business generated total sales of approximately 12.64 million and total profit of approximately 1.47 million.
2. **Product Performance:** Phones generated the highest sub-category sales, while Copiers generated the highest sub-category profit.
3. **Profitability Issue:** Tables generated negative profit despite having substantial sales.
4. **Regional Performance:** The Central region recorded the highest sales and profit among the listed regions.
5. **Market Performance:** APAC recorded the highest sales and profit among the analyzed markets.
6. **Customer Analysis:** The Very High Value customer segment generated the largest share of sales and profit under the project's sales-based segmentation.
7. **Discount Analysis:** Higher discount levels were associated with lower profitability in the analyzed data.
8. **Shipping Analysis:** Standard Class recorded the highest sales and profit, while Same Day had the shortest average shipping time.
9. **Correlation Analysis:** Sales and Shipping Cost showed a strong positive correlation, while Discount and Profit Margin showed a strong negative correlation.

## 📊 Power BI Dashboard

An interactive Power BI report was developed with six analytical pages:

### 1. Executive Summary
- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Profit Margin
- Average Order Value

### 2. Sales Analysis
- Monthly sales trends
- Yearly sales comparison
- Sales by market
- Sales by category
- Sales and profit trends

### 3. Product Analysis
- Sales by category
- Profit by sub-category
- Top 10 products
- Loss-making products
- Product performance comparison

### 4. Customer Analysis
- Top customers by sales
- Top customers by profit
- Customer segment performance
- Customer sales and profit comparison
- Repeat customer analysis

### 5. Regional Analysis
- Sales by country
- Sales by region
- Profit by region
- Sales by market
- Country performance

### 6. Profit Analysis
- Profit by category
- Profit by sub-category
- Discount versus profit
- Monthly profit trends
- Loss-making product analysis

## 💡 Business Recommendations

Based on the analysis, the following recommendations are suggested:

1. Review pricing and discount policies for loss-making products.
2. Investigate the negative profitability of the Tables sub-category.
3. Focus on high-performing products such as Phones and Copiers.
4. Develop customer retention strategies for valuable customers.
5. Investigate markets with relatively low profit compared with sales.
6. Monitor high-discount transactions carefully.
7. Review shipping costs and delivery performance.
8. Improve product-level profitability monitoring.
9. Use monthly sales trends for inventory and business planning.
10. Monitor business KPIs regularly through Power BI dashboards.

## ⚠️ Project Limitations

- The dataset does not contain an explicit customer churn label.
- The dataset does not provide a separate product cost field for independently calculating profit.
- Correlation indicates relationships between variables but does not establish causation.
- IQR outliers were identified for investigation, not automatically removed.
- Customer value groups were created using sales-based thresholds.

## 📁 Suggested Project Structure

```text
Global-Superstore-Business-Analytics/
│
├── Dataset/
│   └── Global Superstore.csv
│
├── Notebooks/
│   └── Global_Superstore_Analysis.ipynb
│
├── PowerBI/
│   └── Global_Superstore_Dashboard.pbix
│
├── Reports/
│   └── Final_Project_Report.pdf
│
├── Images/
│   └── Dashboard_Screenshots/
│
├── README.md
└── requirements.txt
```

*Adjust the filenames and folders to match the files you actually upload.*

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the Jupyter Notebook.
5. Update the dataset file path if required.
6. Run the notebook cells in sequence.
7. Open the `.pbix` file using Microsoft Power BI Desktop to explore the dashboard.

## 🎓 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Feature Engineering
- Business Intelligence
- Power BI Dashboard Development
- DAX Measures
- Business Insights and Recommendations
- Analytical Problem Solving

## 👩‍💻 Project Information

**Project:** Global Superstore Business Analytics  
**Organization:** Devixo Solutions  
**Field:** Data Analytics  
**Tools:** Python, Jupyter Notebook, Power BI, DAX  

---

**Thank you for visiting this project!**

This project demonstrates how raw business data can be transformed into meaningful insights to support better business decisions.
