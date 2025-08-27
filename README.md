🛍️ Retail Sales Exploratory Data Analysis (EDA)

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to uncover customer behavior, product performance, and revenue trends.
The analysis aims to generate actionable insights that help businesses in decision-making, customer retention, and sales optimization.

📂 Dataset Information

Dataset Name: Retail Sales Data (CSV/Excel format)

Number of Records: ~ (fill in based on your dataset)

Columns/Features (example, update as per your dataset):

InvoiceNo → Transaction ID

StockCode → Product code

Description → Product description

Quantity → Number of units purchased

InvoiceDate → Date of purchase

UnitPrice → Price per unit

CustomerID → Unique customer identifier

Country → Country of the customer

🔎 EDA Process & Steps

Data Loading & Cleaning

Handled missing values (e.g., CustomerID, Description).

Removed duplicates and negative quantities.

Converted InvoiceDate into datetime format.

Descriptive Statistics

Summary of numerical features.

Checked data distribution.

Univariate & Bivariate Analysis

Top-selling products.

Monthly/weekly sales trends.

Revenue contribution by product & country.

Customer Segmentation (RFM Analysis)

Recency: Days since last purchase.

Frequency: Number of purchases.

Monetary: Total spend by customer.

Segmented customers into groups (Loyal, New, At-risk).

Visualization & Insights

Used Matplotlib and Seaborn for static plots.

Used Plotly for interactive dashboards (if applied).

💡 Key Insights

Top-selling products drive the majority of revenue.

Holiday seasons show a spike in sales.

A small percentage of loyal customers contribute to a large portion of revenue (80/20 Pareto rule).

Some customers are at risk of churn → potential for targeted marketing.

High sales from a few specific countries (update with dataset results).

🛠️ Tools & Libraries Used

Python 🐍

Jupyter Notebook

Libraries:

pandas → Data cleaning & manipulation

numpy → Numerical operations

matplotlib → Data visualization

seaborn → Statistical plots

plotly → Interactive charts (optional)

📈 Sample Visuals

(Add screenshots of EDA plots like sales trends, RFM heatmaps, top products, etc.)

🔧 How to Run

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Navigate into the project folder:

cd your-repo-name


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook EDA.ipynb

🎯 Outcomes

Retail business can identify loyal customers and design loyalty programs.

Helps in seasonal demand forecasting.

Assists in product portfolio management by identifying high/low-performing products.

Provides a foundation for predictive modeling (future step).
