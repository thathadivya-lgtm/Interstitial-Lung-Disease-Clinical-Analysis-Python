# Clinical Analysis of Interstitial Lung Disease (ILD)

## 📌 Project Overview
This healthcare analytics project focuses on the clinical analysis of Interstitial Lung Disease (ILD) using Python and Power BI. The project analyzes demographic, clinical, and pulmonary function data to identify disease patterns, evaluate severity, and support clinical decision-making through interactive dashboards.

## 🎯 Project Objective
- Analyze clinical, demographic, and pulmonary function characteristics of ILD patients.
- Identify disease patterns and risk factors associated with ILD.
- Evaluate disease severity using pulmonary function parameters.
- Develop interactive Power BI dashboards to support data-driven clinical decision-making.

---

## 📊 Dataset Overview
- **Dataset:** Indian ILD Registry Dataset
- **Number of Records:** 2,005 patients
- **Number of Variables:** 21 clinical features

### Key Variables
- Patient ID
- Age
- Sex
- BMI
- Smoking Status
- Spirometric Pattern
- FVC (Forced Vital Capacity)
- FEV1 (Forced Expiratory Volume in 1 Second)
- FVC % Predicted
- FEV1 % Predicted
- Final Diagnosis
- Diagnostic Category
- Sarcoidosis Stage
- Year of Diagnosis

---

## 🛠️ Tools & Technologies
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Plotly
- **Power BI**
- **Google Colab**
- **GitHub**

---

## 📂 Repository Structure

```text
Interstitial-Lung-Disease-Clinical-Analysis-Python
│
├── Raw_Data
│   └── ILD_Data_2022.xlsx
│
├── Cleaned_Data
│   └── Cleaned_ILD_Data.csv
│
├── PowerBI
│   └── ILD_Dashboard.pbix
│
├── Screenshots
│   ├── Patient_Characteristics_&_Diagnosis_Overview.png
│   ├── Demographic_&_Risk_Factor_Analysis.png
│   └── Clinical_Findings_&_Lung_Function_ Analysis.png
│
├── Clinical_Analysis_of_ILD_Disease.ipynb
├── Clinical Analysis of Interstitial Lung Disease.pptx
└── README.md
```

---

## 🧹 Data Preprocessing
- Removed unnecessary columns.
- Handled missing values using mean and median imputation.
- Created derived columns:
  - Age Category
  - BMI Category
- Performed exploratory data analysis and correlation analysis.

---

## 📈 Dashboards Developed

### 1. Overview Dashboard
- Total Patients
- Average Age
- Average BMI
- Diagnostic Category Distribution
- Spirometric Pattern Distribution
- Smoking Status Distribution
- Gender Distribution

### 2. Demographic & Risk Factor Analysis Dashboard
- Age Category vs Spirometric Pattern
- Gender vs Spirometric Pattern
- Smoking Status vs Spirometric Pattern
- BMI Category vs Spirometric Pattern

### 3. Clinical & Pulmonary Analysis Dashboard
- FVC Distribution Across Diagnostic Categories
- FEV1 Distribution Across Diagnostic Categories
- Sarcoidosis Stage Distribution
- Sarcoidosis Stage vs FVC (%)
- Clinical Correlation Matrix
- FVC vs FEV1 Analysis

---

## 🔍 Key Findings
- Sarcoidosis is the most prevalent diagnostic category.
- Restrictive spirometric pattern is the dominant respiratory pattern.
- Most patients belong to middle-aged and senior age groups.
- The majority of patients are non-smokers.
- FVC and FEV1 show a strong positive correlation.
- Advanced Sarcoidosis stages are associated with reduced FVC and worsening pulmonary function.
- Smoking contributes to obstructive impairment but is not the primary determinant of ILD occurrence.

---

## 💡 Recommendations & Future Enhancements
Future versions of the project can include:
- High-Resolution CT (HRCT) findings
- DLCO measurements
- Oxygen Saturation (SpO₂)
- Six-Minute Walk Test (6MWT)
- Autoimmune biomarker data
- Environmental and occupational exposure history
- Longitudinal follow-up data for predictive modelling

---

## 🎯 Project Outcome
The dashboard transforms complex clinical and pulmonary data into actionable insights that help:
- Assess patient risk factors
- Classify disease subtypes
- Monitor pulmonary function decline
- Identify disease progression patterns
- Support data-driven clinical decision-making

---

## 👩‍💻 Author
**Divya Thatha**

- LinkedIn: https://www.linkedin.com/in/divya-thatha
- GitHub: https://github.com/thathadivya-lgtm
