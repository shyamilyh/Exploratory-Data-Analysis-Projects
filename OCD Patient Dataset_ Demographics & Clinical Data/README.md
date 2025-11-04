# 🧠 OCD Patient Demographics and Clinical Data Analysis  

### 📘 Overview  
This project focuses on the **exploratory and statistical analysis** of a clinical dataset containing demographic and psychological information of patients diagnosed with **Obsessive-Compulsive Disorder (OCD)**.  
The analysis aims to uncover meaningful patterns related to demographics, symptom severity, comorbid conditions, and treatment factors — providing insights that can aid in better understanding OCD prevalence and treatment outcomes.  

---

## ⚙️ Project Workflow  

1. **Data Import & Description**  
   - Loaded and explored a dataset with **17 attributes**, each detailing different aspects of OCD patients such as demographics, clinical measures, and comorbidities.  
   - Key attributes include:  
     - `Age`, `Gender`, `Ethnicity`, `Education Level`, `Duration of Symptoms`,  
     - `Obsession Type`, `Compulsion Type`, `Y-BOCS Scores`, `Depression Diagnosis`, `Anxiety Diagnosis`, and `Medications`.  

2. **Data Cleaning**  
   - Identified **248 missing values** in `Previous Diagnoses` and **386 missing values** in `Medications`.  
   - Handled missing data using appropriate imputation and data transformation techniques.  
   - Verified there were **no duplicate records** and standardized categorical columns.  

3. **Feature Analysis**  
   - Classified columns into **categorical** (e.g., Gender, Marital Status, Diagnosis) and **numerical** (e.g., Age, Duration, Y-BOCS Scores).  
   - Conducted descriptive statistics to understand central tendencies and distributions.  

4. **Demographic Visualization**  
   - Analyzed demographic factors such as **age distribution**, **gender ratio**, and **education levels**.  
   - Visualized the relationships between demographic factors and OCD symptom patterns.  

5. **Clinical Analysis**  
   - Investigated **types of obsessions and compulsions** prevalent among patients.  
   - Studied **family history influence**, **duration of symptoms**, and **comorbid depression/anxiety**.  
   - Explored medication usage patterns and treatment correlations.  

6. **Correlation & Severity Analysis**  
   - Conducted **correlation analysis** between **Y-BOCS Obsession** and **Compulsion scores** to assess symptom severity relationships.  
   - Compared severity trends among patients with and without depression or anxiety comorbidity.  

---

## 📊 Key Findings  

- 🧩 **Missing Data:**  
  - `Previous Diagnoses` → 248 missing entries  
  - `Medications` → 386 missing entries  

- 👥 **Demographics:**  
  - Dataset contained a balanced gender distribution and a wide range of ages.  
  - Most patients reported **moderate education levels**.  

- 💊 **Clinical Observations:**  
  - **Harm-related** and **Contamination** obsessions were most frequent.  
  - **Checking** and **Washing** were the top compulsion types.  
  - Strong correlation found between **Y-BOCS obsession** and **compulsion scores**, indicating consistent symptom severity patterns.  

- 😔 **Comorbidities:**  
  - A significant subset of patients showed **coexisting depression and anxiety** diagnoses.  
  - These patients tended to have **higher Y-BOCS scores**, implying more severe OCD symptoms.  

---

## 🧠 Insights & Analysis  

- **Family history** plays a notable role in symptom recurrence and intensity.  
- **Depression and anxiety comorbidities** are strong indicators of higher symptom severity and longer treatment duration.  
- Certain **obsession-compulsion pairs** (like contamination–washing) exhibit a strong co-occurrence pattern.  
- Missing medication data suggests the need for better clinical record documentation.  

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

The analysis provided a deeper understanding of **OCD’s clinical characteristics** and associated demographic patterns.  
Key takeaways include:  
- Identifying the most prevalent obsession and compulsion types,  
- Establishing links between comorbidities and severity, and  
- Highlighting demographic patterns that could guide personalized treatment plans.  

This study underscores the power of **data-driven insights in mental health research**, helping clinicians and researchers better understand complex psychiatric conditions.  

---

### ✨ Author  
**Shyamily Haridas**  
📫 *Data Scientist & ML Engineer*  
🔗 [LinkedIn](#) | [GitHub](#) | [Portfolio](#)

---
