# Supermarket-Sales-Analysis
##  Project Overview
This project analyzes supermarket sales using Excel, SQL, and Power BI. The goal is to understand sales trends, top-selling products, and customer behavior.
It includes interactive visualizations in Power BI.
## Aim of this Project
  The primary aim of this project are as follows:
  - Visualize Sales Trends: Utilize Excel's Pivot Tables and Charts to create visual representations of sales data, highlighting significant patterns and outliers.
  - Explore Customer Purchase Behavior: Analyze purchasing patterns based on customer demographics such as gender, and geographical factors like branch and city.
  - Interactive Supermarket Dashboard: Design an interactive dashboard using Power BI.
## Data Source Description

* Dataset Title: Supermarket Sales Dataset
* Source: Kaggle Dataset,an online platform for data science and machine learning that provides
thousands of free datasets for practice.
 This dataset comprises sales data from a supermarket operating across two branches,Branch A and Branch B. It captures various attributes related to sales transactions, customer type, and product categories. 
 The dataset contains key details such as:

i. Sales ID	(Unique ID for each transaction)

ii. Branch (Store location)

iii. City (where the branch is located)

iv. Customer Type (Member/Non-Member)

v. Gender (Customer's gender)

vi. Product Name (Name of the product sold)

vii. Product Category (Category of the product)

viii. Unit Price (Price per unit)

ix. Quantity (Number of units purchased)

x. Tax (Tax applied to the sale)

xi. Total Price (Final price after tax)

xii. Reward Points (Points earned per purchase)

## Steps and Tools Used
1. Data Collection and Cleaning

* Tool: Excel
* Purpose: Imported the supermarket sales dataset into Excel for initial review and cleaning. Utilized Excel's features to identify and correct inconsistencies, such as misclassified product categories, ensuring data accuracy for analysis.
  
-![Raw Data](https://github.com/user-attachments/assets/ec6b52c4-2073-49bc-8b56-58e037a974e2)

![Cleaned Data](https://github.com/user-attachments/assets/a8b038ac-d4bb-4508-85fe-d864f09de85d)


2. Data Analysis and Querying

* Tool: SQL
* Purpose: Employed SQL to perform complex queries on the cleaned dataset. This facilitated efficient data manipulation, aggregation, and extraction of specific insights, such as identifying top-selling products and analyzing sales trends over time.
  
![Sales Analysis1](https://github.com/user-attachments/assets/c00a1cc6-6a2c-4c6b-9956-919fcad93ee5)

![Sales Analysis2r2](https://github.com/user-attachments/assets/10361b37-1251-4682-8ad1-7fe837480fba)


3. Data Visualization and Reporting

* Tool: Power BI
* Purpose: Utilized Power BI to create interactive dashboards and visualizations. This enabled a comprehensive representation of the data, highlighting key metrics like sales performance across branches, product profitability, and customer purchasing behavior, thereby aiding in informed decision-making.
  
  ![Dashboard](https://github.com/user-attachments/assets/8607d5e6-87b5-4647-8b70-1cbc2f1b17c7)

4. Pivot Tables
  
* Tool: Excel
* Purpose: Created PivotTables to summarize sales data and identify patterns.
  
![Pivot Table Workbook](https://github.com/user-attachments/assets/1a94ced5-d534-490e-8724-9803d28a8503)

## Findings

* Gender Distribution Across Branches:
  * Branch A: Out of 674 customers, 52.82% are male (356 customers) and 47.18% are female (318 customers).
  * Branch B: Out of 326 customers, 52.76% are male (172 customers) and 47.24% are female (154 customers).
* Profit by Product Line:
  * Highest Profit: The "Personal Care" category leads with a profit of $1,769.66.
  * Lowest Profit: The "Stationery" category reports the lowest profit at $1,356.71.
* Average Unit Price by Product:
  * Highest Average Unit Price: "Shampoo" has the highest average unit price at $2,617.
  * Lowest Average Unit Price: "Apple" has the lowest at $2,006.
* Reward Point Distribution by Product Line:
  * Highest Reward Points: The "Personal Care" category accumulates the highest reward points at 1,435.
  * Lowest Reward Points: The "Fruit" category has the lowest with 951 reward points.
    
 ##  Recommendations
 
* Targeted Marketing for Female Customers: Given the slightly higher male customer base in both branches, implementing marketing strategies aimed at attracting more female customers could help balance the gender distribution and potentially increase sales.
* Promote High-Profit Product Lines: Focus on marketing and promotional efforts for the "Personal Care" category to capitalize on its high profitability. This could include special offers, bundling products, or loyalty rewards.
* Revitalize Stationery Sales: Since "Stationery" yields the lowest profit, consider strategies such as introducing new products, offering discounts, or creating bundled deals to boost interest and sales in this category.
* Adjust Pricing Strategies: Review the pricing of products like "Shampoo" and "Apple" to ensure they are competitively priced. For high-priced items like "Shampoo," consider value-based promotions to justify the cost to customers.
* Enhance Reward Programs for Low-Reward Categories: To encourage more purchases in the "Fruit" category, consider increasing the reward points or offering special promotions to make these products more appealing to customers.

## Conclusion

The analysis highlights specific areas for improvement and opportunity within the supermarket's operations. By addressing the gender imbalance in customer distribution, leveraging high-profit product lines, revitalizing underperforming categories, adjusting pricing strategies, and enhancing reward programs, the supermarket can enhance customer satisfaction and drive increased profitability.





