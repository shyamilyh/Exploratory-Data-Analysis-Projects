# 🎬 Netflix Data Cleaning, Analysis & Visualization

### 📘 Overview  
This project focuses on analyzing Netflix’s catalog data to uncover key trends in **content type distribution, audience ratings, release timelines, and genre diversity**.  
The analysis aims to provide actionable insights into Netflix’s content strategy and evolving entertainment trends over time.

---

## ⚙️ Project Workflow  

1. **Data Import & Overview**  
   - Loaded the dataset `netflix1.csv` containing **8,790 entries** and **10 features**.  
   - Key columns: `show_id`, `type`, `title`, `director`, `country`, `date_added`, `release_year`, `rating`, `duration`, and `listed_in`.

2. **Data Cleaning**  
   - Verified that there were **no missing or duplicate values**.  
   - Ensured uniform formatting for dates and categorical fields.  
   - Filtered the dataset to include **Movies and TV Shows** released between **1925 and 2021** and added to Netflix from **2008 to 2021**.

3. **Feature Exploration**  
   - Extracted and analyzed **content types, ratings, and release years**.  
   - Visualized trends to understand audience preferences and Netflix’s catalog evolution.

4. **Exploratory Data Analysis (EDA)**  
   - Compared **Movies vs. TV Shows** distribution.  
   - Analyzed **rating frequencies** and **content maturity trends**.  
   - Examined **release year patterns** and **genre popularity** over time.  

---

## 📊 Key Findings  

- 🎥 **Movies:** 6,126 entries (**~69.7%**)  
- 📺 **TV Shows:** 2,664 entries (**~30.3%**)  

🔹 **Most Common Rating:**  
- **TV-MA** dominates with **3,205 entries**, reflecting a high volume of content for mature audiences.  
- **Least Common Ratings:** *NC-17* and *UR*, with only 3 entries each.  

📅 **Timeline Insights:**  
- Netflix content spans from **1925 to 2021**.  
- Majority of titles were **added between 2015–2021**, aligning with Netflix’s rapid global expansion.  

🌍 **Geographic Diversity:**  
- The platform includes content from multiple countries, emphasizing Netflix’s global catalog reach.

---

## 🧠 Insights & Business Analysis  

- The majority of Netflix’s content is **movie-based**, though **TV shows** have grown steadily post-2015.  
- The dominance of **TV-MA ratings** suggests a focus on **mature storytelling and adult-oriented content**.  
- **Increased content addition from 2015 onward** coincides with Netflix’s aggressive content acquisition and original production phase.  
- The dataset highlights Netflix’s **global expansion strategy**, bringing in international titles and diverse genres.  

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

This analysis provided a clear view of **Netflix’s content composition, audience targeting, and catalog evolution**.  
By leveraging visual analytics, we identified:  
- Strong focus on **mature-rated content**,  
- Growth in **TV show production**, and  
- Expanding **international content footprint**.  

These findings can assist in **strategic content planning**, **regional targeting**, and **genre diversification** decisions for streaming platforms.

---

## 📂 Folder Structure  

```
Netflix_Data_Cleaning_Analysis_Visualization/
│
└── Netflix_Data_Cleaning,_Analysis_and_Visualization.ipynb   	# Main analysis notebook  
└── README.md                                                 	# Project documentation  
└── Dataset								                             # Dataset 
└── Netflix_Data_Cleaning_Analysis_and_Visualization – Report 	# Report
└── Netflix_Data_Cleaning_Analysis_and_Visualization.pdf       # Notebook PDF

```

---

## 💡 Future Scope  

- Build a **Netflix Insights Dashboard** using Streamlit or Power BI.  
- Perform **genre-based sentiment analysis** using user reviews (if available).  
- Use **machine learning models** to predict popular genres or audience ratings.  

---

### ✨ Author  
**Shyamily Haridas**  
📫 *Data Science Enthusiast | Exploring Insights from Data*  
🔗 [LinkedIn](#) | [GitHub](#) | [Portfolio](#)

---
