# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into customer demographics, purchasing patterns, product preferences, subscription behavior, and revenue trends.

The workflow combines Python for data analysis, SQL for business querying, Power BI for visualization, and Gamma for presentation design. The objective is to transform raw customer data into actionable business insights that support data-driven decision-making.

---

## Dataset

The dataset contains customer shopping transactions across multiple product categories.

### Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Data Includes:**

  * Customer demographics (Age, Gender, Location)
  * Purchase information (Product, Category, Amount)
  * Shopping behavior (Discounts, Reviews, Shipping Type)
  * Subscription status
  * Purchase frequency and previous purchases

### Data Quality

* Missing values identified in the **Review Rating** column.
* Data cleaned and standardized before analysis.

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database

* PostgreSQL
* MySQL
* SQL Server

### Visualization

* Power BI

### Reporting & Presentation

* Microsoft PowerPoint
* Gamma

---

## Project Workflow

### 1. Data Loading

* Imported dataset into Python using Pandas.
* Reviewed dataset structure and data types.
* Generated descriptive statistics.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Explored purchasing behavior and spending patterns.
* Identified trends across categories, age groups, and subscription status.
* Visualized key metrics and distributions.

### 3. Data Cleaning

* Handled missing values.
* Standardized column names.
* Removed redundant fields.
* Created additional features such as:

  * Age Groups
  * Purchase Frequency Metrics

### 4. SQL Analysis

The cleaned dataset was loaded into a relational database and analyzed using SQL.

Key business queries included:

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Comparison
* Subscribers vs Non-Subscribers Analysis
* Customer Segmentation
* Revenue by Age Group
* Top Products by Category
* Repeat Buyer Analysis

### 5. Dashboard Development

Built an interactive Power BI dashboard to monitor:

* Customer Count
* Average Purchase Amount
* Revenue by Category
* Sales by Category
* Customer Segments
* Subscription Trends
* Revenue by Age Group

### 6. Reporting & Presentation

* Documented findings in a business report.
* Created a presentation deck using Gamma for stakeholder communication.

---

## Dashboard Highlights

### Key KPIs

* Total Customers
* Average Purchase Amount
* Average Review Rating
* Total Revenue

### Interactive Filters

* Gender
* Category
* Subscription Status
* Shipping Type

### Visualizations

* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Subscription Distribution
* Customer Segmentation

---

## Key Results

### Customer Insights

* Male customers generated higher overall revenue.
* Loyal customers represented the largest customer segment.
* Subscription adoption remains relatively low compared to non-subscribers.

### Product Insights

* Certain products consistently achieved higher customer ratings.
* Several products showed strong dependency on discount-driven purchases.

### Business Insights

* Express shipping customers demonstrated slightly higher average spending.
* Younger and middle-aged customer groups contributed a significant portion of total revenue.
* Repeat buyers present an opportunity for subscription conversion strategies.

---

## Business Recommendations

* Increase subscription adoption through exclusive member benefits.
* Develop customer loyalty programs for repeat buyers.
* Optimize discount strategies to balance revenue and profitability.
* Promote highly rated and best-selling products.
* Use targeted marketing campaigns for high-value customer segments.

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_data.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── reports/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── presentation/
│   └── Customer_Behavior_Analysis.pptx
│
└── README.md
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### 3. Run Python Analysis

```bash
python customer_behavior_analysis.py
```

### 4. Execute SQL Queries

* Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server.
* Run the SQL scripts available in the `sql/` folder.

### 5. Open Power BI Dashboard

* Open the dashboard file in Power BI Desktop.
* Refresh the data connection if required.

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, covering data cleaning, exploratory analysis, SQL-based business insights, dashboard development, reporting, and presentation. It highlights practical skills in Python, SQL, Power BI, and business storytelling that are commonly required in data analyst and business intelligence roles.

