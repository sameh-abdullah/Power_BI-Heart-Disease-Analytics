# ❤️ Heart Disease Analysis Dashboard (Power BI)

## 📌 Overview
This project presents an interactive **Power BI dashboard** for heart disease analysis. It is designed to explore clinical and lifestyle data in order to uncover patterns, identify key risk factors, and provide actionable insights into the development of heart disease.

The dashboard enables users to analyze how different health metrics and behaviors contribute to heart disease outcomes.

---

## ❗ Problem Statement
Heart disease remains one of the leading causes of death worldwide. However, identifying the combination of factors that contribute to its development can be complex.

This project aims to:
- Analyze patient data to identify **key risk factors**
- Explore relationships between **clinical indicators and lifestyle habits**
- Provide a **data-driven view of heart disease patterns**

---

## 📂 Dataset
- **Source:** Excel file (`heart_disease.xlsx`)
- **Main Table:** `Heart_disease_table`

### Key Attributes:
- **Demographics:** Age, Gender  
- **Clinical Metrics:** Blood Pressure, Cholesterol Level, BMI  
- **Lifestyle Factors:** Smoking, Exercise Habits, Alcohol Consumption  
- **Medical History:** Family Heart Disease, Diabetes  
- **Biomarkers:** HDL, LDL, CRP Level, Homocysteine Level  
- **Other Factors:** Stress Level, Sleep Hours, Sugar Consumption  
- **Target Variable:** Heart Disease Status  

---

## 🧠 Data Model
The model is built around one main fact table with supporting calculated tables for better segmentation:

### 🔹 Main Table
- `Heart_disease_table` → Core dataset containing all patient records

### 🔹 Supporting Tables
- `Family_Smoking_Diabete`  
  - Groups: Smoking, Family Heart Disease, Diabetes, High Blood Pressure  

- `HDL_LDL`  
  - Groups cholesterol-related indicators (High LDL, Low HDL)  

- `Stress_Alcohol`  
  - Groups lifestyle factors (Stress Level, Sugar Consumption)  

---

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query** (Data Cleaning & Transformation)
- **DAX (Data Analysis Expressions)** for measures and calculations
- **Excel** (Data Source)

---

## 📈 Dashboard Features
- Interactive filters (Age, Gender, Lifestyle, Medical Conditions)
- KPI cards for quick insights
- Comparative analysis (Heart Disease vs No Heart Disease)
- Risk factor segmentation
- Visualizations:
  - Bar charts  
  - Pie charts  
  - Trend analysis  
  - Distribution visuals  

---

## 🔍 Key Insights
- Identifies the **most influential risk factors** for heart disease  
- Highlights relationships between:
  - Cholesterol levels (HDL/LDL)
  - Lifestyle habits (smoking, stress, alcohol)
  - Medical conditions (diabetes, blood pressure)
- Provides a clear comparison between affected and non-affected patients  

---

## 🖼️ Dashboard Preview
**Interactive Dashboard** <a href="https://app.powerbi.com/view?r=eyJrIjoiYmJmMjUxZTMtZWQwMS00ZTkwLTgwOGEtOGVjYzAwMTY0YTVlIiwidCI6IjE1ODgyNjJkLTIzZmItNDNiNC1iZDZlLWJjZTQ5YzhlNjE4NiIsImMiOjh9"> Disease Analysis Dashboard</a></br>

**Project Dashboard Image**
<img src="https://github.com/sameh-abdullah/Power_BI-Heart-Disease-Analytics/blob/main/Images/Screenshot%202026-05-03%20212815.png" width="1000" heigh="1000"/>

---

## 📁 Project Structure
 ├── dataset/ <a href="">Dataset (Excel file)</a> <br>
 ├── images/ <a href=""> Dashboard screenshots</a> <br>
 ├── reports template/ <a href="report template"> Power BI file (.pbit)</a> <br>
 └── README.md


---

## 🎯 Project Value
This project demonstrates:
- Data modeling in Power BI  
- Use of DAX for analytical calculations  
- Building interactive dashboards  
- Translating raw data into meaningful insights  

---

## 👤 Author
**Sameh Abdullah**  
**LinkedIn**: <a href="https://linkedin.com/in/sameh-abdullah-961554176"> My Profile </a> 

---
