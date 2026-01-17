# Marketing Analytics Dashboard (Python)

This project builds an **interactive marketing analytics dashboard** using **Python and data visualization libraries** to explore **customer demographics, purchasing behavior, income distribution, and campaign performance**.

The dashboard consolidates multiple insights into a **single visual report** to support strategic marketing decision-making.

---

## 📌 Project Overview

The objective of this project is to:
- Analyze customer demographic patterns (age, income, education, marital status)
- Understand spending behavior across different product categories
- Evaluate purchasing channels and engagement levels
- Measure response rates to marketing campaigns
- Present insights through a unified, multi-plot dashboard

The final output is a **15-panel marketing dashboard** summarizing key customer and sales metrics.

---

## 📊 Dataset Description

The dataset contains **2,205 customer records** with **39 features**, including:

### Demographics
- `Age`
- `Income`
- `Education Level`
- `Marital Status`
- `Kidhome`, `Teenhome`

### Purchasing & Spending
- `MntWines`
- `MntFruits`
- `MntMeatProducts`
- `MntFishProducts`
- `MntSweetProducts`
- `MntGoldProds`
- `MntTotal`
- `MntRegularProds`

### Engagement & Campaign Data
- `NumWebPurchases`
- `NumCatalogPurchases`
- `NumStorePurchases`
- `NumDealsPurchases`
- `NumWebVisitsMonth`
- `AcceptedCmp1 – AcceptedCmp5`
- `AcceptedCmpOverall`

---

## 🧹 Data Preparation

- Removed **184 duplicate records**
- Verified **no missing values**
- Created derived features:
  - `Age_Group` (age binning)
  - `Income_Group` (income segmentation)
  - `numKids` (total children)
  - `fSize` (family size)
  - `f_Seg` (family segment classification)

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Seaborn** – Statistical visualization
- **Matplotlib** – Dashboard construction
- **Jupyter Notebook**

---

## 📈 Dashboard Components

The dashboard includes the following visual insights:

1. Customer age distribution  
2. Customer income distribution  
3. Average spending by product category (Age Group)  
4. Average spending by product category (Income Group)  
5. Purchases by channel (Age Group)  
6. Purchases by channel (Income Group)  
7. Total expenditure by age group  
8. Total expenditure by income group  
9. Customer distribution by marital status  
10. Income distribution histogram  
11. Campaign response rate (pie chart)  
12. Customer distribution by education level  
13. Total expenditure by family segment  
14. Purchases by channel (Family segment)  
15. Purchases by channel (Education level)  

All plots are displayed in a **5×3 grid dashboard layout** with a styled background image.

---

