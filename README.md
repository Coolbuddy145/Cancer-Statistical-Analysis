# 🧬 Cancer Statistical Analysis (2015–2024)

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-lightblue)


### 📊 Project Overview
This project analyzes global cancer patient data (2015–2024) to uncover the relationships between genetic, lifestyle, and environmental risk factors and their impact on treatment costs, survival years, and disease severity.

The analysis combines **statistical methods**, **visualizations**, and **data-driven insights** to highlight how risk factors contribute to cancer outcomes worldwide.

---

### 🧠 Objectives
- Explore and visualize cancer trends across countries and years  
- Identify correlations between risk factors and patient survival  
- Analyze cost variations by cancer stage and type  
- Apply **Pearson** and **Spearman** correlation for statistical inference  
- Provide actionable insights for data-driven healthcare analysis  

---

### 🧾 Dataset Information
**Source:** Global Cancer Patients Dataset (2015–2024)

| Feature | Description |
|----------|--------------|
| `Patient_ID` | Unique ID for each patient |
| `Age`, `Gender`, `Country_Region`, `Year` | Demographic information |
| `Genetic_Risk`, `Air_Pollution`, `Alcohol_Use`, `Smoking`, `Obesity_Level` | Lifestyle & environmental factors |
| `Cancer_Type`, `Cancer_Stage` | Disease type and progression |
| `Treatment_Cost_USD`, `Survival_Years`, `Target_Severity_Score` | Outcome measures |

---

### 🧩 Tools & Libraries
- **Python**
- **Pandas, NumPy** → Data handling
- **Matplotlib, Seaborn, Plotly** → Visualization
- **SciPy** → Correlation & Hypothesis Testing


---

### 📈 Key Analyses Performed
1. **Exploratory Data Analysis (EDA)**
   - Distribution of age, gender, and cancer type
   - Year-wise trends in treatment cost
   - Cross-country comparison of severity scores

2. **Correlation & Hypothesis Testing**
   - Pearson and Spearman correlation between:
     - Survival Years vs. Treatment Cost
     - Risk Factors vs. Severity Score
   - Hypothesis significance via p-values

3. **Risk Factor Visualization**
   - Multi-plot grid comparing each risk factor vs. Survival Years
   - Custom color-coded plots for interpretability

---

### 🔍 Key Insights
- Strong positive correlation between **treatment cost** and **survival years**  
- **Smoking**, **obesity**, and **genetic risk** emerged as major severity drivers  
- **Air pollution** showed moderate correlation with severity but varied by country  

---

### 🚀 Future Improvements
- Add machine learning (e.g., Linear Regression or Random Forest) to predict survival or cost  
- Build Power BI or Plotly Dashboard for presentation  
- Enhance with statistical summaries using `statsmodels`

---

### 📚 Learnings
- Statistical inference through `scipy.stats`  
- Difference between **Pearson** and **Spearman** correlation  
- Visual storytelling in healthcare analytics  
- Data preprocessing and multi-variable visualization  

---

### 👨‍💻 Author
**Zaid Khan**  
*Data Analyst | Aspiring ML Specialist | Storytelling through Data*

---



