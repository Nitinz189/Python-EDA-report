# 🩺 Medical Dataset EDA Report

This repository contains an exploratory data analysis (EDA) of a medical dataset using Python. The goal is to uncover patterns, trends, and relationships between patient attributes and medical outcomes such as heart issues and blood sugar levels.

## 📊 Distribution & Summary Stats

- **Heart Rate**  
  - What is the average, minimum, and maximum heart rate in the dataset?

- **Blood Pressure Across Age Groups**  
  - How does systolic and diastolic pressure vary across age groups?

- **Troponin & CK-MB by Gender**  
  - What are the average Troponin and CK-MB levels for each gender?

---

## 🧮 Group-Wise Comparisons

- **Gender Comparison**  
  - Compare heart rate and blood pressure between male and female patients.

- **Diagnosis-Based Sugar Levels**  
  - What’s the average blood sugar level for patients with positive vs negative diagnoses?

- **CK-MB & Troponin by Age Bracket**  
  - How do CK-MB and Troponin levels differ across age brackets (e.g., <40, 40–60, >60)?

---

## 🩺 Clinical Associations

- **Blood Pressure and Diagnosis**  
  - Among patients with high blood pressure (e.g. systolic > 140), what percentage had positive results?

---

## 📌 Data Quality Checks

- **Extreme Values**  
  - How many patients have unusually high heart rate values (e.g. 1111)?

- **Constant or Duplicate Entries**  
  - Are there duplicate or constant values (e.g., CK-MB = 300 across many rows)?

- **Suspicious Troponin Records**  
  - Are any Troponin readings missing or zero where a positive diagnosis exists?
