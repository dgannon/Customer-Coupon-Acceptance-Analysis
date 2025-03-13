# 🛍️ Customer Coupon Acceptance Analysis 📊  

## 📌 Overview  
This project analyzes customer behavior in response to receiving coupons while driving. The dataset, sourced from the UCI Machine Learning Repository, contains information about customers’ demographics, trip context, and coupon details. The goal is to explore the key factors influencing whether a customer will **accept** or **reject** a coupon using **data visualization and statistical analysis**.  

## 🎯 Project Objectives  
- Understand customer preferences for different coupon types.  
- Identify patterns based on **age, location, time, passenger type, and income**.  
- Compare acceptance rates for **frequent vs. infrequent visitors** of bars, coffee houses, and restaurants.  
- Provide actionable insights for **better coupon targeting** and **marketing strategies**.  

---

## 📂 Repository Structure  
Customer-Coupon-Acceptance-Analysis/ 
│── data/ # Dataset 
│ ├── coupons.csv
│── notebooks/ # Jupyter Notebook with full analysis 
│ ├── prompt.ipynb.ipynb
│── README.md # Project Overview & Usage Instructions 
│── requirements.txt # Python dependencies

---

## 📊 Data Summary  
The dataset consists of **12,684 records** with the following key attributes:  
✔️ **User Info:** Age, gender, marital status, occupation, income level  
✔️ **Trip Context:** Destination, time of day, weather, passengers  
✔️ **Coupon Details:** Type of business, expiration period  
✔️ **Outcome Variable (Y):** Whether the customer accepted (`1`) or rejected (`0`) the coupon  

---

## 🔍 Key Findings & Insights  
✅ **Frequent bar-goers (more than 3 times a month) accept bar coupons ~77% of the time.**  
✅ **Coffee shop visitors who frequent cafes more than twice a month are ~67% more likely to accept coupons.**  
✅ **Time of day and weather impact coupon acceptance—people are less likely to use coupons in bad weather or at early hours.**  
✅ **People with lower incomes are slightly more inclined to accept restaurant coupons (<$50k vs. >$50k).**  
✅ **Having kids as passengers drastically reduces bar coupon acceptance.**  

### 📌 Actionable Recommendations  
🔹 **Target frequent visitors** (bars, restaurants, coffee shops) with personalized offers.  
🔹 **Optimize timing** of coupon distribution based on customer behavior patterns.  
🔹 **Consider contextual factors** like weather and passenger presence for better targeting.  
🔹 **Use AI-driven recommendations** to enhance location-based coupon delivery.  

---

## 📈 Visualizations  
The project includes **several data visualizations**, such as:  
📊 **Bar Charts** - Distribution of coupon types, acceptance rates  
📉 **Histograms** - Temperature distribution and its impact on acceptance  
📌 **Scatter Plots** - Relationship between coupon types and customer behaviors  
📊 **Correlation Heatmaps** - Identifying the strongest predictive factors  

---

## ⚙️ Installation & Usage  
### 🔹 1. Clone the Repository  
```bash
git clone https://github.com/YOUR_USERNAME/Customer-Coupon-Acceptance-Analysis.git
cd Customer-Coupon-Acceptance-Analysis

open the prompt.ipynb in jypter Notebook and run all the cells