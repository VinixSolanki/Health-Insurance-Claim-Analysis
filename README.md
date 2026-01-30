#  Health Insurance Claim Analysis

## Project Overview

This project delivers a comprehensive **exploratory data analysis (EDA)** of a health insurance claims dataset.  
It uncovers patterns, highlights business insights, and provides actionable recommendations to improve claims management, efficiency, and risk detection.

---

## Objectives

- Analyze **claim distribution**, types and provider specialties  
- Explore the **impact of demographics** and submission methods  
- Identify **cost drivers, outliers, and anomalies**  
- Generate insights for **reducing denials** and enhancing processing efficiency  

---

## Dataset Details

- **Rows:** 4,500  
- **Columns:** 17  
- **Key Features:**  
  - `ClaimID`, `ClaimAmount`, `ClaimDate`, `ClaimType`, `ClaimStatus`  
  - `PatientAge`, `PatientGender`, `PatientIncome`, `PatientMaritalStatus`, `PatientEmploymentStatus`  
  - `ProviderSpecialty`, `ProviderLocation`  
  - `ClaimSubmissionMethod`, `DiagnosisCode`, `ProcedureCode`  
  - `PatientID`, `ProviderID`

---

## Analysis Performed

- Data cleaning and preprocessing (handling missing values, data types)
- Exploratory Data Analysis (EDA) using **Pandas**, **Matplotlib**, and **Seaborn**
- Trend analysis of **claims over time**
- Income-based segmentation and comparison with **Claim Amount**
- Visualizations for:
  - Claim Status distribution  
  - Claim Type and Provider Specialty  
  - Submission Method trends  
  - Relationship between income and claim amount  
  - Time-series trendline of claim approvals  

---

## Key Insights

- **Approved, Denied and Pending claims** are evenly distributed, offering a good balance for analytics.
- **Outpatient** and **Routine** claims dominate, especially in **Cardiology** and **Pediatrics**.
- **Claim amounts are normally distributed** with an average of approximately ₹5,000 and show **no significant correlation** with patient income.
- **Paper submissions** are still common, and shifting to digital submissions can improve processing speed and data accuracy.
- **Trendline analysis** shows higher approval activity at the start and end of each quarter, indicating workload patterns.


---

## Recommendations

- **Encourage digital submissions** to improve claim accuracy and reduce manual errors.  
- Review **high-denial specialties** (e.g., Cardiology) for process improvement.  
- Implement **outlier monitoring systems** to flag potential fraud or data anomalies.  
- Track **claim frequency and recency** to build predictive models for approval likelihood.

---

## Tools & Technologies

| Tool / Library | Purpose |
|-----------------|----------|
| **Python (Pandas, NumPy)** | Data cleaning and manipulation |
| **Matplotlib / Seaborn** | Data visualization |
| **Jupyter Notebook** | Interactive analysis and documentation |

---

## 
```bash
git clone https://github.com/<your-username>/Health-Insurance-Claim-Analysis.git
cd Health-Insurance-Claim-Analysis
