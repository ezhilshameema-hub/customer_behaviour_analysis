# customer_behaviour_analysis
📌 Overview

This is an end-to-end Data Analytics project that analyzes customer purchasing behavior using Python, SQL, and Power BI.

The project demonstrates the complete data workflow:

Data loading and cleaning in Python

Exploratory Data Analysis (EDA)

Database integration (PostgreSQL / MySQL / SQL Server)

Business query analysis using SQL

Interactive dashboard creation in Power BI

Final report and presentation (Gamma PPT)

The goal of the project is to generate actionable business insights on revenue, customer segmentation, product performance, and subscription behavior.

📂 Dataset

~3,900 transaction records

18 structured features

Customer demographic, product, and transaction details

Key Columns:

Customer ID

Age, Gender, Location

Subscription Status

Item Purchased & Category

Purchase Amount (USD)

Shipping Type

Discount Applied

Review Rating

Payment Method

Purchase Frequency

🛠️ Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & EDA
Jupyter Notebook	Analysis environment
PostgreSQL / MySQL / SQL Server	Database storage & querying
SQLAlchemy + psycopg2	Python–Database connection
SQL	Business analysis queries
Power BI	Dashboard development
Gamma	Project presentation

📋 Project Steps
1️⃣ Data Loading & EDA (Python)

Imported dataset using pandas

Checked structure using df.info() and df.describe()

Identified missing values

Performed exploratory analysis on:

Revenue trends

Customer distribution

Product categories

2️⃣ Data Cleaning & Feature Engineering

Handled missing values (median imputation)

Standardized column names (snake_case)

Created new features:

age_group

Customer segments (New / Returning / Loyal)

Removed redundant columns

Ensured consistent data types

3️⃣ Database Integration

Connected Python to PostgreSQL using SQLAlchemy

Loaded cleaned data into database table

Verified schema and structure

Ran structured SQL queries

4️⃣ SQL Business Analysis

Sample business questions answered:

Revenue by Gender

Revenue by Age Group

Top 3 Products per Category

Subscribers vs Non-Subscribers Revenue

High-Spending Discount Users

Customer Segmentation Analysis

Shipping Type Spend Comparison

Repeat Purchase Analysis

Used:

GROUP BY

JOIN

CASE

CTE (WITH)

Window functions (ROW_NUMBER())

5️⃣ Power BI Dashboard

Built an interactive dashboard including:

KPI Cards:

Total Customers

Total Revenue

Average Purchase Value

Revenue by Category

Revenue by Age Group

Subscription Status Breakdown

Top Products

Slicers:

Gender

Category

Subscription Status

Shipping Type

The dashboard allows dynamic filtering and business-driven analysis.

📊 Key Insights

Majority of revenue comes from repeat customers

Subscribers contribute higher average spending

Young adults generate the highest revenue share

Certain products are highly discount-dependent

Express shipping users spend more on average

📁 Project Structure
project-folder/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── customer_dashboard.pbix
│
├── report/
│   └── final_report.pdf
│
├── presentation/
│   └── presentation.pptx
│
└── README.md

How to Run
1️⃣ Clone Repository
git clone https://github.com/your-username/project-name.git
cd project-name
2️⃣ Install Required Libraries
pip install pandas sqlalchemy psycopg2-binary jupyter
3️⃣ Setup Database

Install PostgreSQL / MySQL / SQL Server

Create a new database

Update credentials in notebook

username = "your_username"
password = "your_password"
host = "localhost"
port = "5432"
database = "database_name"
4️⃣ Run Notebook
jupyter notebook

Run all cells to:

Clean data

Push data to database

5️⃣ Run SQL Queries

Open your database tool (pgAdmin / SSMS / MySQL Workbench)

Execute the SQL script

6️⃣ Open Power BI

Open .pbix file

Refresh data connection

Explore dashboard

📈 Business Value

This project demonstrates:

Strong SQL proficiency

Data cleaning and transformation skills

Database integration knowledge

Analytical thinking

Dashboard design capabilities

End-to-end project execution

👩‍💻 Author

Ezhil Shameema
Aspiring Data Analyst | Python | SQL | Power BI




