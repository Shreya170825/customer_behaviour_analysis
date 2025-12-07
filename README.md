# customer_behaviour_analysis
This project analyzes customer shopping behavior using SQL, Python (Pandas), and Power BI. It includes data cleaning, feature engineering, exploratory analysis, and an interactive Power BI dashboard. Key insights include revenue trends, age-group analysis, subscription behavior, discount usage, and category performance.
📊 Customer Behavior Analysis | Python · SQL · Power BI

An end-to-end data analytics project analyzing customer shopping behavior using Python, MySQL, and Power BI.
This project covers data cleaning, exploratory analysis, feature engineering, SQL insights, and interactive dashboarding—making it a complete portfolio project for Data Analytics.

🚀 Project Overview

The goal of this project is to understand customer purchase patterns, behavior, and revenue drivers using a structured analytics workflow.
The project includes:

Loading and cleaning the dataset in Python

Performing Exploratory Data Analysis (EDA)

Creating new features (Age Group, Purchase Frequency, etc.)

Running analytical SQL queries in MySQL

Building a professional Power BI dashboard to visualize insights

📂 Repository Structure
├── customer_shopping_behavior.csv      # Dataset
├── customer_trends.ipynb               # Python EDA & feature engineering
├── customer_behaviour.sql              # SQL queries for analysis
├── customer_behavior_dashboard.pbix     # Power BI dashboard
└── README.md                           # Project documentation

📁 Dataset

The dataset contains 3,900 customer transactions, including:

Customer demographics (Age, Gender)

Product category & item purchased

Purchase amount

Review ratings

Subscription status

Shipping type

Discounts, promo codes, previous purchases

🧠 Key Questions Answered

✔ Which age group generates the highest revenue?
✔ Which categories and products perform best?
✔ Do subscribers spend more than non-subscribers?
✔ How do discounts affect purchase amount?
✔ Which shipping types are most preferred?
✔ What is the average purchase and review behavior by customer segment?

🐍 Python Workflow

In customer_trends.ipynb, the following steps were performed:

🔹 1. Load & clean dataset

Normalized column names

Handled missing values

Converted data types

🔹 2. Feature Engineering

Created Age Groups using quantiles

Created Purchase Frequency Days

Dropped redundant columns

🔹 3. Exploratory Analysis

Gender-wise purchase patterns

Category-wise revenue

Subscription impact on spending

Correlation between reviews & purchase behavior

🛢 SQL Analysis (MySQL)

The customer_behaviour.sql file includes queries such as:

Total revenue by gender

Customers using discounts but spending above average

Top products with highest review ratings

Shipping type performance

Subscribers vs non-subscribers (average spend & revenue)

Discount usage analysis

Revenue by age group

These SQL insights help validate and support the Python findings.

📊 Power BI Dashboard

The Power BI dashboard visualizes:

Total customers

Average purchase amount

Average review rating

% of customers by subscription status

Revenue by category

Sales by age group

Shipping type usage

Customer segmentation insights

The dashboard provides an interactive way to explore patterns and trends.

🛠 Tools & Technologies
Component	Technology Used
Data Cleaning	Python, Pandas
EDA	Python, Jupyter Notebook
Database Queries	MySQL
Visualization	Power BI
File Management	GitHub
🧾 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/Shreya170825/customer_behaviour_analysis.git

2️⃣ Open the dataset

Use customer_shopping_behavior.csv in Python or SQL.

3️⃣ Run the Python Notebook

Open in Jupyter Notebook:

customer_trends.ipynb

4️⃣ Run SQL Queries

Import the dataset into MySQL
Execute:

customer_behaviour.sql

5️⃣ Open Power BI Dashboard

Load:

customer_behavior_dashboard.pbix

📌 Results & Insights

Middle-aged customers contribute the highest revenue

Clothing category dominates both sales and revenue

Subscribers spend significantly more than non-subscribers

Discount users do not always spend less—many high-spenders use discounts

Express and Free Shipping are the most commonly used shipping methods

These insights help understand customer behavior and improve marketing strategies.

📜 License

This project is licensed under the MIT License.
