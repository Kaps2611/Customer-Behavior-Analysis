# Customer-Behavior-Analysis
## 📌 Overview:
This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, product preferences, customer segments, and subscription behavior. The analysis combines Python, MySQL, SQL, and Power BI to deliver end-to-end data analytics, supported by a detailed report and presentation.

## 📁 Dataset:
- Source: Customer Shopping Behavior dataset
- Rows: ~3,900
- Columns: 18
- Key Data Includes:
- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase details (Category, Item, Purchase Amount, Season)
- Shopping behavior (Discount, Previous Purchases, Review Rating, Shipping Type)
- Data Issues: Missing values in review ratings

## 🛠 Tools & Technologies:
- Python (Pandas, NumPy, Matplotlib/Seaborn)
- MySQL Server / MySQL Workbench
- SQL
- Power BI
- Gamma (for PPT creation)
- Excel

## 🔄 Steps (Project Workflow):
- Data Loading (Python)
  - Loaded the dataset using pandas.
  - Performed initial inspection using .info() and .describe().
- Exploratory Data Analysis (EDA)
  - Analyzed distributions, trends, and relationships.
  - Studied spending patterns, ratings, discounts, and subscriptions.
- Data Cleaning & Transformation
  - Handled missing values in review ratings using median imputation.
  - Standardized column names.
  - Created derived features like age groups and customer segments.
  - Removed redundant columns for consistency.
- Database Integration
  - Connected Python to MySQL Server using SQLAlchemy.
  - Loaded the cleaned dataset into MySQL tables.
- SQL Analysis
  - Wrote SQL queries to analyze:
  - Revenue by gender and age group
  - Subscribers vs non-subscribers
  - High-spending customers
  - Top products and categories
  - Discount impact on sales
  - Customer segmentation
 
- Dashboard Development
  - Built an interactive Power BI dashboard to visualize KPIs and trends.
- Reporting & Presentation
  - Created a detailed project report.
  - Designed a professional PPT using Gamma for storytelling and insights.

## 📊 Dashboard:
- The Power BI dashboard highlights:
- Revenue and purchase trends
- Customer segmentation
- Subscription impact
- Top-performing products and categories
- Discount and shipping behavior
<img width="1351" height="734" alt="Customer_Behavior Dashboard" src="https://github.com/user-attachments/assets/74029e3c-2b1a-4543-81ae-9218c91c3cce" />

## ✅ Results & Insights:
- Subscribers contribute higher average revenue compared to non-subscribers.
- Repeat and loyal customers drive a major share of sales.
- Discounts increase purchase volume but impact margins.
- Certain age groups and shipping types generate higher revenue.
- Top-rated products align strongly with higher sales.
 
