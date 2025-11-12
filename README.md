🛒 Customer Shopping Behavior Analysis


📊 End-to-End Data Analysis Project using Python, SQL, and Power BI
🧠 Business Problem

A leading retail company wants to understand its customers’ shopping behavior to improve sales, satisfaction, and long-term loyalty.
They’ve observed changes in purchasing patterns across demographics, product categories, and channels, and want to identify what drives purchases and repeat buying — such as discounts, reviews, or seasonal trends.

Business Question:
How can the company leverage consumer shopping data to identify trends, improve engagement, and optimize marketing & product strategies?

🎯 Project Objective

1. Analyze 3,900 customer transactions to uncover insights about:

2. Spending patterns and revenue distribution

3. Product and category performance

4. Subscription and loyalty behavior

5. Impact of discounts and shipping types

🧰 Tools & Technologies Used
Tool	Purpose
Python (Pandas, NumPy, Matplotlib, Seaborn)	  - Data cleaning, exploration, and feature engineering
PostgreSQL / SQL  -	Business transaction analysis and querying
Power BI  -	Interactive dashboard for visualization
GitHub -	Version control and project documentation

🧩 Project Workflow
1️⃣ Data Preparation (Python)

* Loaded raw dataset with 3,900 rows & 18 columns
* Cleaned and standardized columns (snake_case naming)
* Handled missing data (imputed review_rating by category median)
* Created new features:
* age_group (based on customer age)
* purchase_frequency_days (derived from purchase dates)
* Loaded cleaned dataset into PostgreSQL for structured analysis

2️⃣ SQL Analysis

* Key business queries executed:

* Revenue comparison by gender

* Top 5 highest-rated products

* Average purchase amount by shipping type
 
* Discount users vs. non-discount spenders

* Subscribers vs. non-subscribers revenue comparison

* Top products per category

* Customer segmentation (New, Returning, Loyal)

* Repeat buyers and their subscription likelihood

* Revenue by age group

3️⃣ Power BI Dashboard

Designed an interactive dashboard showcasing:

Total revenue and sales trends

Top-performing products & categories

Customer demographics and behavior patterns

Subscription vs. non-subscription insights

Discount and shipping impact on sales

<p align="center">
  <img src="https://raw.githubusercontent.com/CHARITHREDDY30/Customer_Behavior_Analysis/main/Screenshot%202025-11-12%20170602.png" 
       alt="Power BI Dashboard Preview" width="800"/>
  <br>
  <em>Power BI Dashboard – Customer Insights Overview</em>
</p>

📈 Key Insights

1. Females generated higher total revenue compared to males.

2. Express shipping users spent more than standard shipping users.

3. Subscribers contributed significantly higher average spending.

4. Discount-heavy products boosted sales but lowered profit margins.

5. Loyal customers (5+ purchases) were more likely to subscribe.

💼 Business Recommendations

*Introduce loyalty programs to reward repeat customers.
*Offer exclusive subscription benefits to increase retention.
*Optimize discount policies to balance volume and profit.
*Highlight top-rated & best-selling products in campaign.
*Focus marketing on high-revenue age groups and express-shipping users.

📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── data_cleaning_analysis.ipynb
│
├── sql/
│   └── business_analysis_queries.sql
│
├── dashboard/
│   └── PowerBI_Customer_Shopping.pbix
│
├── reports/
│   ├── Customer_Shopping_Behavior_Analysis.pdf
│   └── Business_Problem_Document.pdf
│
├── README.md
└── requirements.txt

🧩 Results Summary

This project successfully delivered:

* A clean and structured database ready for BI reporting.

* SQL-driven insights on key business metrics.

* A visually rich Power BI dashboard for management decision-making.

🧑‍💻 Author

Charith T
📍 Tirupati, Andhra Pradesh, India
📧 Charithreddytatekalava@gmail.com
💼 CharithReddy Tatekalava

🐙 GitHub Profile
