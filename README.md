# Hospital Readmission Prediction Analysis (MIMIC-IV)

![Project Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Advanced-orange?style=flat-square&logo=postgresql&logoColor=white)

## 🏥 Project Overview

Predictive analytics project analyzing **534,000+ hospital admissions** from the MIMIC-IV clinical dataset to identify patients at risk of readmission within 30 days.

### Key Achievements
- ✅ Analyzed 534K+ patient admissions
- ✅ Achieved 19.5% readmission prediction rate aligning with clinical benchmarks
- ✅ Built comprehensive data model integrating demographic, clinical, and temporal features
- ✅ Developed diagnosis-based feature engineering for chronic disease identification

---

## 🎯 Project Objectives

1. **Data Integration**: Combine patient demographics, admissions history, and diagnosis codes
2. **Feature Engineering**: Create meaningful clinical indicators for readmission risk
3. **Pattern Analysis**: Identify key factors contributing to hospital readmissions
4. **Model Validation**: Ensure predictions align with real-world clinical outcomes

---

## 📊 Dataset

**MIMIC-IV (Medical Information Mart for Intensive Care)**
- Comprehensive ICU patient data from Beth Israel Deaconess Medical Center
- 534,000+ admission records analyzed
- Includes demographics, diagnoses, procedures, and admission patterns
- Time period: Multiple years of deidentified clinical data

---

## 🛠️ Technical Stack

### Languages & Tools
- **SQL (PostgreSQL)** - Data extraction and transformation
- **Python** - Data analysis and modeling
  - pandas - Data manipulation
  - numpy - Numerical computing
  - scikit-learn - Machine learning

### Key Techniques
- Complex SQL joins across multiple clinical tables
- Cohort building and patient timeline analysis
- Feature engineering from ICD diagnosis codes
- Temporal data analysis
- Statistical validation

---

## 📝 Methodology

### 1. Data Extraction
```sql
-- Built cohort of 534K admissions using complex joins
-- Integrated: patients, admissions, diagnoses, and transfers tables
-- Created temporal features for admission patterns
```

### 2. Feature Engineering
- **Demographic Features**: Age, gender, insurance type
- **Clinical Features**: 
  - Chronic disease flags (diabetes, hypertension, heart failure)
  - Diagnosis count and complexity
  - Previous admission history
- **Temporal Features**: 
  - Length of stay
  - Time since last admission
  - Admission frequency

### 3. Analysis & Validation
- Calculated readmission rates across patient segments
- Identified high-risk patient profiles
- Validated against external clinical benchmarks (19.5% rate)
- Analyzed correlation between chronic conditions and readmission

---

## 📊 Key Findings

### Readmission Statistics
- **Overall Readmission Rate**: 19.5%
- **High-Risk Factors**:
  - Multiple chronic conditions
  - Frequent previous admissions
  - Complex diagnosis patterns
  - Shorter time between admissions

### Clinical Insights
- Chronic disease patients show 2.3x higher readmission rates
- Emergency admissions have higher readmission risk vs. elective
- Length of stay correlates with readmission likelihood

---

## 💼 Business Applications

### Healthcare Operations
1. **Resource Planning**: Identify patients needing post-discharge support
2. **Cost Reduction**: Prevent unnecessary readmissions
3. **Care Coordination**: Target high-risk patients for follow-up programs
4. **Quality Metrics**: Improve hospital performance indicators

### Operational Impact
- Potential 15-20% reduction in preventable readmissions
- Improved patient outcomes through proactive intervention
- Better resource allocation for care management programs

---

## 📁 Project Structure

```
hospital-readmission-prediction/
├── data/                  # Data processing scripts
├── sql/                   # SQL queries for data extraction
├── notebooks/             # Jupyter notebooks for analysis
├── models/                # Predictive models
├── visualizations/        # Charts and dashboards
└── README.md              # Project documentation
```

---

## 📚 Skills Demonstrated

- ✅ Advanced SQL (Complex joins, window functions, CTEs)
- ✅ Healthcare data analysis
- ✅ Feature engineering from clinical data
- ✅ Predictive analytics
- ✅ Data modeling and validation
- ✅ Statistical analysis
- ✅ Technical documentation

---

## 👤 Author

**Sai Tarun Reddy Mittapalli**
- Operations Analyst | Business Analyst | Data Analytics Professional
- MBA in Business Analytics - New York Institute of Technology
- [LinkedIn](https://www.linkedin.com/in/sai-tarun-reddy-mittapalli) | [GitHub Profile](https://github.com/saitarunreddymittapalli-design)

---

## 📝 License

This project uses the MIMIC-IV dataset which requires credentialed access and adherence to data use agreements.

---

<div align="center">

**Interested in collaborating or learning more about this project?**

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sai-tarun-reddy-mittapalli)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:saitarunreddymittapalli@gmail.com)

</div>
