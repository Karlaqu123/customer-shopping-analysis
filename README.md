# 📊 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project demonstrates an end-to-end **data analytics workflow** using Python, PostgreSQL, Power BI, and Gamma. The objective is to transform raw customer shopping data into actionable business insights through data cleaning, exploratory analysis, SQL querying, dashboard creation, and reporting.

The project covers the complete analytics pipeline—from loading the dataset in Python to presenting the final insights in a professional presentation.

---

## 🎯 Objectives

- Load and inspect raw customer transaction data
- Perform exploratory data analysis (EDA)
- Clean and prepare the dataset for analysis
- Store and query data using PostgreSQL
- Build an interactive Power BI dashboard
- Summarize findings in a written report
- Create a presentation using Gamma

---

## 📂 Dataset

The dataset contains customer shopping transactions with the following fields:

| Column | Description |
|--------|-------------|
| `customer_id` | Unique identifier for each customer |
| `age` | Customer's age |
| `gender` | Customer's gender (Male/Female) |
| `item_purchased` | Product name |
| `category` | Product category (Clothing, Footwear, Accessories, Outerwear) |
| `purchase_amount` | Transaction value in USD |
| `location` | US state where purchase was made |
| `size` | Product size (S, M, L, XL) |
| `color` | Product color |
| `season` | Season of purchase (Spring, Summer, Fall, Winter) |
| `review_rating` | Customer rating (2.5 - 5.0) |
| `subscription_status` | Whether customer has subscription (Yes/No) |
| `shipping_type` | Shipping method used |
| `discount_applied` | Whether discount was applied (Yes/No) |
| `previous_purchases` | Number of prior purchases |
| `payment_method` | Payment type (Credit Card, PayPal, Venmo, etc.) |
| `frequency_of_purchases` | Purchase frequency pattern |

**Derived/Engineered Columns:**
| Column | Description |
|--------|-------------|
| `age_group` | Categorized age ranges (e.g., 18-25, 26-35, etc.) |
| `purchase_frequency_days` | Numeric representation of purchase frequency |

**Total Records:** 3,900 transactions

**Source:** Public customer shopping behavior dataset

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python (pandas)** | Data loading, EDA, and cleaning |
| **PostgreSQL** | Data storage and SQL analysis |
| **Power BI** | Interactive dashboard and KPI visualization |
| **Microsoft Word / PDF** | Analytical report |
| **Gamma** | Presentation and storytelling |

---

## 🔄 Project Workflow

### 1. Data Loading (Python)

- Imported the dataset into Python
- Inspected structure, data types, and missing values
- Verified dataset quality before analysis

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand customer behavior:

- Distribution of purchase amounts
- Sales by category
- Customer demographics
- Seasonal trends
- Payment method usage
- Frequency of purchases

### 3. Data Cleaning

Key cleaning steps included:

- Removing unnecessary columns
- Handling missing values
- Standardizing column names
- Correcting inconsistent values
- Validating discount and promo code fields
- Preparing data for SQL and Power BI

### 4. PostgreSQL Analysis

The cleaned dataset was loaded into PostgreSQL for analytical querying.

#### Example analyses

- Total revenue by category
- Top-selling products
- Average purchase amount
- Customer purchase frequency
- Revenue by season
- Ranking products within categories
- Window functions and CTEs

### 5. Power BI Dashboard

Built an interactive dashboard to visualize business insights.

#### Dashboard Features

- KPI cards (Revenue, Orders, Customers)
- Sales by category
- Top products
- Seasonal performance
- Payment method analysis
- Customer purchase behavior

---

## 📝 Report

A detailed analytical report was created summarizing:

- Business problem
- Methodology
- EDA findings
- SQL analysis
- Dashboard insights
- Recommendations

File: `project_summary.docx`

---

## 🎤 Presentation (Gamma)

A presentation was developed using **Gamma** to communicate the project story and findings effectively.

### Presentation Includes

- Project overview
- Dataset summary
- EDA highlights
- SQL insights
- Dashboard walkthrough
- Business recommendations
- Conclusion

File: `customer_shopping_behavior_analysis.pptx`

---

## 📁 Repository Structure

```text
customer-shopping-analysis/
│
├── README.md
├── customer_shopping_behavior.csv
├── data_cleaning.ipynb
├── eda_analysis.ipynb
├── sql_analysis.sql
├── powerbi_dashboard.pbix
├── dashboard.png
├── Customer_Shopping_Behavior_Report.pdf
└── Customer_Shopping_Behavior_Presentation.pdf
```

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- SQL for Business Analytics
- PostgreSQL
- Power BI Dashboard Development
- Data Storytelling
- Reporting and Presentation

---

## 📚 What I Learned

Through this project, I strengthened my ability to:

- Work with real-world datasets
- Clean and validate data
- Use SQL for analytical problem-solving
- Design interactive dashboards
- Communicate insights to non-technical audiences
- Present findings in a professional format

---

## 👤 Author

**Karl Muñoz**

- GitHub: https://github.com/Karlaqu123
- LinkedIn: *www.linkedin.com/in/muñoz-karl-vincent-7b8247394*

---

## ⭐ Acknowledgment

This project was created as part of my data analytics portfolio to practice and demonstrate an end-to-end analytics workflow using Python, PostgreSQL, Power BI, and Gamma.
