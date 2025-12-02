## Sales Data in Alteryx - Cleaning & Analysis (Python Project)

________________________________________
📘 Overview
This project focuses on data cleaning, analysis, and visualization using Python.
It explores sales data from a retail business to uncover key insights about profitability, customer behavior, payment methods, and product performance in different regions.
The analysis was performed using Pandas, NumPy, and Matplotlib, with a focus on writing clean, efficient, and interpretable code.

________________________________________
🎯 Objectives
The main goals of this project were to:
1.	Clean and preprocess the raw dataset for analysis.
2.	Explore sales and profit trends across time, product categories, and customers.
3.	Identify top-performing regions, customers, and products.
4.	Compare profitability across different payment methods (COD, EFT, Debit Card, Credit Card).
5.	Create visual insights to support business decision-making.

________________________________________
🧰 Tools & Libraries
Tool	Purpose
Python	Core programming language
Pandas	Data manipulation and cleaning
NumPy	Numerical operations
Matplotlib / Seaborn	Data visualization
Jupyter Notebook	Interactive data analysis

________________________________________
Data Cleaning Steps
1.	Handled Missing Values
2.	Removed Duplicates
3.	Converted Data Types, Converted numeric and date columns appropriately
4.	Created New Columns for Profit and Month monthly analysis

________________________________________
📊 Exploratory Data Analysis (EDA)

1. Monthly Sales and Profit Trend
Visualized how sales and profit changed across months:
Insight:
Sales peaked in December, while profit margins were highest around November, December, suggesting holiday sales impact.

2. Top 10 Most Profitable Customers
A small group of customers contributes disproportionately to total profit, potential for loyalty rewards or targeted marketing.

3. Profit by Category
Insight:
Some product categories yield high revenue but low profit margins, suggesting the need for pricing review.

4. Top 10 Orders by Profit (with Key Details)
Displayed top 10 orders with columns: Order ID, Customer Name, Profit, and Region.
Insight:
High-profit orders were concentrated in specific regions useful for optimizing logistics and promotions.

5. Profit by Region
Insight:
Some regions outperform others consistently, strong case for regional marketing focus.

6. Payment Method Analysis
Four columns for payment methods:
•	COD (Cash on Delivery)
•	EFT (Electronic Funds Transfer)
•	DebitCard
•	CreditCard

a. Payment Method Distribution (Pie Chart)
Insight:
EFT and Credit Card payments dominate transactions, while COD is least used, showing customer trust in digital payment options.

b. Payment Method by Profit (Bar Chart)
Insight:
Credit Card and EFT sales generated the highest profits, suggesting smoother payment experiences drive higher-value transactions.

7. Most Profitable Product
Insight:
A few high-value products contribute significantly to profit, potential for focused inventory investment.

8. Executive Summary (from print statements)
Using Python print() and f-strings, we summarized findings:
Quick Takeaways:
•	December drives the highest sales.
•	Credit Card and EFT transactions lead in profit.
•	Top 10 customers are highly valuable to overall performance.
•	Certain regions have strong sales potential.

________________________________________
📈 Visualizations Summary

Visualization	Purpose
Line Chart	Monthly Sales and Profit Trend
Bar Chart	Profit by Category / Region
Pie Chart	Payment Method Distribution
Bar Chart	Payment Method by Profit
Bar Chart	Top 10 Profitable Customers
Combined Subplots	Sales vs Profit Comparison

______________
Next Steps

•	Build a dashboard using Plotly Dash or Power BI.
•	Integrate ML models to predict future sales or customer churn.
•	Expand the dataset with marketing and demographic information.
________________________________________
Key Skills Demonstrated

•	Data Cleaning & Wrangling
•	Exploratory Data Analysis (EDA)
•	Feature Engineering
•	Visualization & Insight Communication
•	Python (Pandas, Matplotlib, Seaborn)


