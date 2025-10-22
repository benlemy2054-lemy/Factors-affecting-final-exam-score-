# 📘 Factors That Influence Final Exam Performance

![Image](https://github.com/user-attachments/assets/97836f31-673b-482d-8e72-15acd736f56d)

## 🎯 Business Question  
**What are the key factors that influence whether a student passes or fails the final exam?**

---

## 💡 Purpose  
This project aims to identify the major habits and background factors that influence students’ final exam results.  
The findings can help both educators and students understand which academic and personal factors most strongly predict success.

---

## 🧩 Analytical Questions  
1. How do **study hours** correlate with final exam scores?  
2. Does **higher attendance** lead to better results?  
3. Is there an **optimal range of sleep hours** for better performance?  

---

## 📊 Data Source  
- **Dataset:** `project work 344.xlsx`  
- **Sheet Used:** `projectwork344`  
- **Source:** [Kaggle.com](https://www.kaggle.com)  
- **Number of Students:** 200  
- **Data Quality:** Clean and complete; no missing key variables.  

---

## 🧠 Data Preparation  
1. Created a **Pass/Fail** column using the Excel `IF` formula based on exam score thresholds.  
2. Conducted **descriptive statistics** (mean, median, range) for numerical variables.  
3. Built **pivot tables** to analyze the distribution of pass/fail outcomes.  
4. Generated **visualizations** (histogram and scatter plots) to explore factor relationships.  
5. Performed **correlation** and **regression analyses** to determine which factors have the greatest effect on exam results.  
6. Designed **Excel** and **Power BI dashboards** for summary visualization.  

---

## 📈 Descriptive Statistics  

| Variable | Mean | Median | Min | Max |
|-----------|-------|--------|------|------|
| Study Hours | **6.33 hrs** | 6.15 | 1.0 | 12.0 |
| Sleep Hours | **6.62 hrs** | 6.70 | 4.0 | 9.0 |
| Attendance | **74.83%** | 75.25 | 50.3 | 100.0 |
| Previous Score | **66.8** | 67.5 | 40 | 95 |
| Exam Score | **33.96** | 34.05 | 17.1 | 51.3 |

---

## 🔗 Correlation Analysis  

| Relationship | Correlation (r) | Strength |
|---------------|-----------------|-----------|
| Study Hours ↔ Exam Score | **0.78** | Strong positive |
| Sleep Hours ↔ Exam Score | **0.19** | Weak positive |
| Attendance ↔ Exam Score | **0.23** | Moderate positive |
| Previous Score ↔ Exam Score | **0.43** | Moderate positive |

> ✅ **Interpretation:** Study hours have the strongest influence on exam performance, followed by previous scores and attendance.

---

## 📉 Regression Insights  
Regression analysis showed that:  
- **Study hours** have the largest positive coefficient → more study time significantly improves performance.  
- **Attendance** and **previous scores** also have meaningful positive impacts.  
- **Sleep hours** have a smaller, yet beneficial effect — balanced rest supports better focus.

---

## 📊 Visualizations  

### 📈 Exam Score Distribution  
![Exam Score Distribution](hist_exam_score.png)

### 🔍 Relationships Between Factors and Exam Score  
![Scatter Relationships](scatter_relationships.png)

*(Make sure both images are in your repository folder, next to this README file.)*

---

## 🔍 Key Findings  
- Students who **study more hours** tend to score higher.  
- **Attendance** improves academic consistency and overall results.  
- **Balanced sleep** (6–8 hours) supports better cognitive performance.  
- **Previous academic success** is a reliable predictor of future results.  

---

## 🧰 Tools & Technologies  
- **Microsoft Excel** – Descriptive statistics, correlation, regression, and dashboard design.  
- **Power BI** – Advanced visualization and interactive dashboards.  
- **Kaggle** – Data sourcing and initial dataset.  
  

---

## 🗂️ Project Structure  

  

---
I am open to collabolaration on data analysis, statistical analysis, and visualisation related projects, you can reach me via email @ benlemy2054@gmail.com
