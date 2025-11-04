# ☕ Coffee Sales Data Analysis

### 📘 Overview  
This project analyzes **coffee sales data** to uncover patterns in customer behavior, sales performance, and payment preferences.  
The goal is to support **data-driven decision-making** for improving marketing strategies, menu offerings, and operational efficiency.

---

## ⚙️ Project Workflow  

1. **Data Loading & Exploration**  
   - Loaded the dataset and reviewed its structure and key statistics.  

2. **Data Cleaning**  
   - Identified **89 missing values** in the `card` column, representing **cash payments**.  
   - Verified **no duplicate records** in the dataset.  
   - Replaced missing card values with `"Cash"` for accurate analysis.  

3. **Feature Engineering**  
   - Extracted time-based features — **Time, Hour, Day, Week, and Month** — from the timestamp column.  
   - Enabled identification of peak sales hours and seasonal patterns.  

4. **Exploratory Data Analysis (EDA)**  
   - Visualized sales by **coffee type**, **payment mode**, and **time of day**.  
   - Analyzed total cups sold, trends across weeks and months, and top-selling items.  

---

## 📊 Key Findings  

- 🥇 **Top-selling Coffee:** *Americano with Milk*  
- 🥈 Followed by: *Latte* and *Cappuccino*  
- 💳 **Payment Breakdown:**  
  - 1044 transactions via **Card**  
  - 89 transactions via **Cash**  
- 🕐 **Sales Duration:** March 1, 2024 – July 31, 2024  
- 🌅 **Peak Hours:** Morning and mid-afternoon show the highest sales activity  

---

## 🧠 Insights & Business Impact  

- Customers prefer **milk-based coffee** over plain espresso variants.  
- The majority of payments are **cashless**, indicating digital adoption.  
- **Targeted promotions** during morning and afternoon hours could boost revenue.  
- Insights help in planning **inventory**, **staff schedules**, and **marketing campaigns**.  

---

## 🧰 Tech Stack  

| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## ✅ Results & Conclusion  

- Discovered valuable sales insights and customer preferences using data analysis.  
- Enabled actionable strategies for business improvement and operational optimization.  
- Demonstrated practical use of **data cleaning**, **feature engineering**, and **visual analytics** to extract meaningful patterns.  

---

## 📂 Folder Structure  

```
Coffee_Sales_Data_Analysis/
│
├── Coffee_Sales_Data_Analysis.ipynb      # Main analysis notebook  
├── README.md                             # Project documentation  
└── coffee_sales                          # Dataset 
└── Coffee_Sales_Data_Analysis - Report   # Report                         
``` 

---

### ✨ Author  
**Shyamily Haridas**  
📫 *Data Science Enthusiast | Exploring Insights from Data*  
🔗 [LinkedIn](#) | [GitHub](#) | [Portfolio](#)

---
