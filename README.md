# Customer_Behaviour_Analysis
Customer Behaviour Analysis — End-to-End Data Analytics Project using Python, SQL and Power BI.

---
📋 **Project Overview**
This project analyzes a dataset of 3,900+ customer shopping transactions to uncover valuable insights about customer behavior, purchase patterns, and revenue drivers. The analysis combines data cleaning, exploratory data analysis (EDA), and SQL-based business intelligence queries to answer critical business questions.

---

📂 ** Dataset**
- Total Records: 3,900
- Total Columns: 18
- Missing Values: 37 in Review Rating
- Data Includes: Customer demographics, purchase details, shopping behavior, ratings, discounts, subscriptions, and shipping information.

---
🛠️ **Tools & Technologies**
- Python(Pandas) – Data Cleaning, EDA & Feature Engineering
- Jupyter Notebook - Interactive Data Analysis Environment
- PostgreSQL – SQL Analysis & Business Queries
- Power BI – Interactive Dashboard & Visualization
  
---
📁 **Project Structure**
Customer Trends Data Analysis/
│
├── customer_shopping_behavior.csv          # Raw dataset
├── Customer_Shopping_Behaviour_Analysis.ipynb  # Python analysis notebook
├── Customer_Shopping_Behavior.sql          # SQL queries for business insights
├── Customer_Behavior_Dashboard.pbix        # Power BI dashboard file
└── README.md                               # Project documentation

---
🔍 **Analysis Workflow** 
1. **Data Cleaning & Preprocessing (Python)**
 - Data Cleaning & Preparation
 - Data Loading: Imported dataset using Pandas.
 - Missing Values: Filled missing review_rating using category-wise median.
 - Column Standardization: Standardized column names and renamed purchase_amount.
 - Feature Engineering: Created age_group and purchase_frequency_days features.
 - Data Quality: Removed duplicate promo_code_used column.
 - Database Export: Loaded cleaned data into PostgreSQL for SQL analysis.

 2. **SQL Analysis & Business Intelligence**
The SQL analysis covers key business questions:
* Revenue Analysis: Gender-based revenue and discount impact
* Product Performance: Top-rated products and discount usage
* Shipping Analysis: Standard vs. Express shipping performance
* Customer Behavior:Subscription impact, customer segmentation, and repeat buyers
* Category Insights: Top 3 products by category
* Demographic Insights: Revenue contribution by age group

3. **Interactive Dashboard**
 Key Metrics: 3.9K Customers | $59.76 Avg. Purchase | 3.75 Avg. Rating
- Subscription Analysis: Subscribers vs. Non-subscribers
- Revenue Insights: Revenue by Category & Age Group
- Sales Performance: Sales by Category & Age Group
- Interactive Filters: Subscription, Gender, Category & Shipping Type
The dashboard provides real-time insights for business decision-making and trend analysis.

4. **Report & Presentation**
* Report: Documented key findings, insights, and business recommendations.
* Presentation: Created a clear, visually engaging presentation highlighting insights and actionable recommendations for stakeholders.
---
💡 **Key Insights**
The analysis provides insights into:
* Customer spending patterns by demographics
* Impact of discounts and subscriptions
* Product performance and customer satisfaction
* Shopping frequency and customer loyalty
* Shipping preferences and spending behavior
* Age-group and category-wise revenue contribution
---
🎯 **Conclusion**
 *This project demonstrates an end-to-end Data Analytics workflow, starting from raw customer transaction data and progressing through data cleaning, exploratory analysis, database integration, SQL-based business analysis, and interactive Power BI visualization.*
