# Customer Shopping Behavior Analysis

## Project Overvie
Understanding customer purchasing behavior is critical for businesses to optimize marketing strategies, improve product positioning, and increase revenue.

This project analyzes **3,900 customer transactions** across multiple product categories to uncover patterns in purchasing behavior, customer segmentation, product popularity, and subscription trends.

The analysis combines **Python for data preparation, PostgreSQL and SQL for business analysis, and Power BI for interactive visualization**, creating a complete end-to-end data analytics workflow.

---

## Business Problem
Retail businesses collect large volumes of transactional data but often struggle to transform that data into actionable insights.

This project aims to answer key business questions such as:

- Which customer segments generate the highest revenue?
- Which products are most popular across categories?
- How do discounts influence purchasing behavior?
- Are subscription users more valuable than non-subscribers?
- Which age groups contribute most to overall revenue?

---

## Dataset Information
The dataset contains customer shopping transaction data with:

- **3,900 rows**
- **18 columns**
- Customer demographics
- Product information
- Purchase behavior
- Subscription and discount usage

### Key Features
- Customer demographics *(Age, Gender, Location)*
- Purchase details *(Category, Item Purchased, Purchase Amount)*
- Shopping behavior *(Discount Applied, Promo Code Used)*
- Customer activity metrics *(Previous Purchases, Frequency of Purchases)*
- Review ratings and shipping preferences

Some missing values were identified in the **Review Rating** column and handled during data preprocessing.

---

## Data Processing (Python)

Data preparation was performed using **Python and Pandas**.

### Steps Performed
- Dataset loading and inspection
- Missing value handling
- Column standardization *(snake_case naming)*
- Feature engineering
- Data validation checks

### Feature Engineering
New analytical features were created:

- **age_group** → customer age segmentation  
- **purchase_frequency_days** → purchase behavior metric

Cleaned data was then loaded into **PostgreSQL** for SQL-based analysis.

---

## SQL Business Analysis

Using **PostgreSQL**, multiple analytical queries were performed.

### Key Analyses
- Revenue distribution by gender
- High-spending customers who used discounts
- Top 5 highest rated products
- Purchase comparison by shipping type
- Revenue comparison between subscribers and non-subscribers
- Discount-dependent products
- Customer segmentation *(New, Returning, Loyal)*
- Top 3 products per category
- Repeat buyers vs subscription trends
- Revenue contribution by age group

These analyses helped uncover patterns in **customer purchasing behavior and product performance**.

---

## Power BI Dashboard

An interactive dashboard was developed to visualize insights.

### Dashboard Highlights
- Total customers and average purchase metrics
- Revenue distribution by category
- Sales trends by age group
- Subscription distribution
- Category performance analysis

The dashboard provides **clear business insights through visual analytics**.

---

## Key Business Insights
- Loyal customers represent the majority of the customer base.
- Some products show strong dependency on discounts.
- Specific age groups contribute higher revenue.
- Subscription customers show different purchasing patterns.
- Product popularity varies across categories.

---


## Project Workflow

Raw Dataset  
↓  
Data Cleaning *(Python / Pandas)*  
↓  
Database Storage *(PostgreSQL)*  
↓  
Business Analysis *(SQL)*  
↓  
Visualization *(Power BI Dashboard)*  

---


## Tools & Technologies
- Python *(Pandas)*
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

## Author

**Prahlad Somapurkar**  
Data Analytics | SQL | Python | Power BI
