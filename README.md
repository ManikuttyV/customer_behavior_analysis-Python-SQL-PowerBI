# customer_behavior_analysis-Python-SQL-PowerBI
# 🛍️ Customer Shopping Behavior Analysis  

## 📌 Project Overview  
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The goal is to uncover insights into **customer segments, spending patterns, product preferences, and subscription behavior** to support data-driven business decisions.

---

## 📊 Dataset Summary  
- **Total Records:** 3,900  
- **Total Features:** 18  
- **Missing Values:** 37 (handled during preprocessing)

### Key Features:
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item, Category, Purchase Amount, Season, Size, Color  
- **Behavioral Data:** Discounts, Promo Code Usage, Purchase Frequency, Review Ratings, Shipping Type  

---

## 🧹 Data Preprocessing (Python)  
Performed using **Pandas & NumPy**  

- Data cleaning and structure validation  
- Handled missing values using **median imputation**  
- Standardized column names (snake_case)  
- Feature engineering:
  - Age group segmentation  
  - Purchase frequency calculation  
- Removed redundant columns  
- Loaded cleaned data into **MySQL** for further analysis  

---

## 🗄️ SQL Analysis (Business Insights)  
Conducted in **MySQL** to answer key business questions:

- 💰 Revenue comparison by gender  
- 🛍️ High-spending customers using discounts  
- ⭐ Top-rated products  
- 🚚 Shipping type vs purchase behavior  
- 👥 Subscribers vs non-subscribers analysis  
- 🏷️ Discount-heavy product categories  
- 🔁 Customer segmentation (New, Returning, Loyal)  
- 📦 Top products by category  
- 📈 Revenue contribution by age group  

---

## 📊 Dashboard (Power BI)  
An interactive dashboard was created to visualize key insights:

### Key Highlights:
- Revenue distribution by gender & age group  
- Category-wise performance  
- Customer segmentation insights  
- Discount and subscription impact  
- Shipping behavior analysis  

---

## 🔍 Key Insights  
- Male customers generated significantly higher revenue  
- Non-subscribers contribute the majority of total revenue  
- Discounts effectively increase spending among customers  
- Loyal customers form the largest segment  
- Revenue is fairly balanced across age groups  

---

## 💡 Business Recommendations  
- 📈 **Increase Subscriptions:** Offer exclusive benefits  
- 🎯 **Targeted Marketing:** Focus on high-value segments  
- 🎁 **Improve Loyalty Programs:** Reward repeat buyers  
- 💸 **Optimize Discounts:** Balance revenue and profit  
- 🏆 **Promote Top Products:** Highlight high-rated items  

---

## 🛠️ Tools & Technologies  
- **Python** (Pandas, NumPy)  
- **MySQL**  
- **Power BI**  
- **Excel**  

---


