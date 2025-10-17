# 🎗️ Cancer Statistical Analysis

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-lightblue)

A comprehensive statistical analysis of global cancer patient data from 2015-2024, exploring demographic patterns, risk factors, treatment costs, and survival metrics.

## 📊 Project Overview

This project analyzes a dataset of 50,000 cancer patients worldwide to uncover patterns in cancer types, risk factors, treatment outcomes, and demographic distributions. The analysis provides valuable insights for healthcare professionals, researchers, and policy makers.

## 📁 Dataset Information

**File:** `global_cancer_patients_2015_2024.csv`

**Size:** 50,000 records × 15 columns

### Dataset Features:
- **Patient_ID**: Unique patient identifier
- **Age**: Patient age at diagnosis (20-89 years)
- **Gender**: Patient gender (Male, Female, Other)
- **Country_Region**: Geographic location
- **Year**: Diagnosis year (2015-2024)
- **Risk Factors**: Genetic_Risk, Air_Pollution, Alcohol_Use, Smoking, Obesity_Level
- **Medical Information**: Cancer_Type, Cancer_Stage
- **Treatment Metrics**: Treatment_Cost_USD, Survival_Years, Target_Severity_Score

## 🛠️ Technical Stack

- **Python 3.7+**
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Environment**: Jupyter Notebook

## 📈 Key Analyses Performed

### 1. Data Quality Assessment
- Checked for missing values (none found)
- Verified no duplicate records
- Examined data types and structure

### 2. Descriptive Statistics
- Age distribution analysis with histograms and KDE plots
- Gender distribution across patient population
- Statistical summaries of numerical variables

### 3. Demographic Insights
- **Age Range**: 20-89 years
- **Mean Age**: 54.42 years
- **Gender Distribution**: Balanced across Male, Female, and Other categories
- **Temporal Coverage**: 2015-2024

## 🎯 Key Findings

### Age Distribution:
- Broad representation across all age groups
- Mean age: 54.42 ± 20.22 years
- Interquartile Range: 37-72 years
- Supports comprehensive age-based comparative analysis

### Data Quality:
- Clean dataset with no missing values or duplicates
- Well-structured with appropriate data types
- Balanced gender representation

## 📊 Visualizations

The project includes:
- Histogram and KDE plots for age distribution
- Statistical distribution analysis
- Demographic pattern visualizations

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
