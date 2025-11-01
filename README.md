<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/1dbb6970-1214-459d-8a94-631945177c22" />


# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories. The goal is to uncover insights into:
- Spending patterns  
- Customer segments  
- Product preferences  
- Subscription behavior  

These insights can guide **data-driven retail strategies** such as loyalty programs, discount policies, and targeted marketing.

---

## Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - Customer demographics (Age, Gender, Location, Subscription Status)  
  - Purchase details (Item, Category, Amount, Season, Size, Color)  
  - Shopping behavior (Discounts, Promo Codes, Frequency, Reviews, Shipping Type)  
- **Missing Data:** 37 values in *Review Rating* column (handled via imputation)

---

## Methodology
### 1. Data Preparation (Python)
- Cleaned and standardized dataset using **pandas**  
- Imputed missing values with median ratings per category  
- Engineered new features (e.g., `age_group`, `purchase_frequency_days`)  
- Ensured consistency between discount and promo code fields  

### 2. SQL Analysis (MySQL)
Performed structured queries to answer key business questions, including:  
- Revenue by gender and age group  
- High-spending discount users  
- Top-rated and most-purchased products  
- Shipping type comparisons  
- Subscriber vs. non-subscriber spending  
- Customer segmentation (New, Returning, Loyal)  

### 3. Visualization (Power BI)
Built an **interactive dashboard** to present insights visually:  
- Revenue and sales by category  
- Subscription breakdown  
- Age group contributions  
- Shipping preferences  

---

## Key Insights
- **Male customers** generated ~2x revenue compared to females  
- **Loyal customers** dominate the base (3,116 out of 3,900)  
- **Discount-heavy products**: Hats, Sneakers, Coats, Sweaters, Pants  
- **Subscribers** spend slightly less on average, but non-subscribers drive higher total revenue  
- **Young Adults** contribute the highest revenue among age groups  

---

## Business Recommendations
- Strengthen **subscription benefits** to increase adoption  
- Launch **loyalty programs** to reward repeat buyers  
- Reassess **discount policies** to balance sales and margins  
- Highlight **top-rated products** in campaigns  
- Target **high-revenue age groups** and **express shipping users**  

---

## Tech Stack
- **Python** (pandas, numpy, matplotlib, seaborn)  
- **MySQL** (for structured business queries)  
- **Power BI** (for dashboarding and storytelling)  
