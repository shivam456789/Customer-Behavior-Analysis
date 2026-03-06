# Customer-Behavior-Analysis
A comprehensive data analytics project that explores customer purchasing patterns, spending behavior, and product preferences using Python, SQL, and Power BI.

# 📌 Project Overview

This project analyzes transactional data from 3,900 purchases across multiple product categories to uncover actionable insights into customer behavior. The analysis covers demographic trends, discount usage, subscription impact, and product performance to support strategic business decisions.

#### Key Business Questions:

How do spending patterns differ across gender, age, and subscription status?

Which products are most dependent on discounts?

What drives customer loyalty and repeat purchases?

How do shipping types affect average purchase amounts?



# 🛠️ Tools & Technologies

Tool	:   Purpose

Python (Pandas, NumPy) :	Data cleaning, preprocessing, feature engineering

PostgreSQL :	Structured querying and business logic analysis

Power BI :	Interactive dashboard design and visualization

Jupyter Notebook	:  Exploratory Data Analysis (EDA)

Excel/PPT :	Final report and presentation

# 📁 Dataset Description

Rows: 3,900

Columns: 18

Key Features:

Demographics: Age, Gender, Location, Subscription Status

Purchase: Item, Category, Amount, Season, Size, Color

Behavior: Discount Applied, Promo Code Used, Review Rating, Shipping Type, Previous Purchases

Data Quality: 37 missing values in Review Rating (imputed with median per category)

# 🔄 Workflow

#### 1. Data Preparation (Python) 
Loaded dataset using Pandas

Cleaned column names, handled missing values

Created new features: age_group, purchase_frequency_days

Removed redundant columns (e.g., promo_code_used)

Loaded cleaned data into PostgreSQL

### 2. Exploratory Data Analysis (Python)
Summary statistics and data structure review

Distribution analysis of purchases, ratings, and discounts

Identified patterns across customer segments

### 3. SQL Analysis (PostgreSQL)
Performed 10 business-focused queries including:

Revenue by gender and age group

Top-rated products and discount-dependent items

Subscriber vs. non-subscriber spending behavior

Customer segmentation (Loyal, Returning, New)

Shipping type impact on purchase amount

### 4. Dashboard (Power BI)
Built an interactive dashboard featuring:

Key KPIs: Total Revenue, Avg. Purchase, Customer Count

Revenue trends by age group and gender

Product performance and discount usage

Subscription behavior and shipping analysis

### 5. Reporting
Compiled findings into a structured report

Created a presentation summarizing insights and recommendations

# 📊 Key Insights

Revenue Split: Female customers contributed $75K, while males generated $158K in revenue.

Top Product by Rating: Gloves (Avg. Rating: 3.86)

Discount Dependency: 50% of Hat purchases used a discount—highest among all products.

Customer Segments: 3,116 loyal customers identified vs. 833 new customers.

Shipping Impact: Express shipping users spent ~$2 more on average than Standard shipping users.

Subscribers: Only 27% of customers are subscribed, but they show strong spending behavior.

# 💡 Business Recommendations

Boost Subscriptions: Highlight exclusive benefits to convert more non-subscribers.

Loyalty Programs: Reward repeat buyers to grow the "Loyal" segment.

Review Discount Strategy: Balance volume with margins—especially for heavily discounted items.

Product Campaigns: Feature top-rated and best-selling items in marketing.

Targeted Marketing: Focus on high-revenue age groups and express shipping users.
