# Emergency Room Analysis: Hospital Patient Insights Dashboard

## 📊 Project Overview  
This project is a **Power BI dashboard** developed to analyze patient data from hospitals in **Saudi Arabia**, such as *Central Hospital in Dammam*. It visualizes and monitors critical healthcare metrics related to emergency room performance and patient flow.

## 🎯 Project Purpose  
The main goal of this project is to deliver an **interactive dashboard** that helps hospital staff—especially doctors and management—track and improve key performance indicators (KPIs) across emergency department operations. The dashboard aims to support data-driven decision-making to enhance patient care and resource allocation.

---

## 📂 Datasets  
The dataset used in this project includes detailed records for each patient. It contains information such as:

- **Patient Info**: `patient_id`, `gender`, `nationality`, `date_of_birth`, `age_group`
- **Visit Info**: `date_arrived`, `time_arrived`, `arrival_shift`, `arrival_method`, `is_weekend`, `is_night_visit`
- **Triage & Treatment**: `date_tiraged`, `time_tiraged`, `triage_response_time_minutes`, `triage_compliance_flag`
- **Treatment & Completion**: `date_treatment_start`, `time_treatment_start`, `time_treatment`, `treatment_duration_minutes`
- **Admission & Outcome**: `admit_date`, `admit_time`, `is_admitted`, `outcome_code`, `disposition_time`, `admission_processing_time_minutes`
- **Performance Metrics**: `waiting_time_minutes`, `total_er_duration_minutes`, `pharmacy_response_time_minutes`
- **Satisfaction & Cost**: `patient_satisfaction_score`, `visit_cost`, `return_visit_72h`, `complication_flag`
- **Other Info**: `doctor_code`, `department_code`, `hospital_code`, `clinic_name`, `diagnosis_code`

---

## 📌 Analysis Objectives  

### **Main Dashboard**
The **Main Dashboard** provides high-level insights and tracks the following KPIs:

1. **Total Number of Patients** with % change compared to the last month  
2. **Average Triage Time** and its monthly change  
3. **Average Waiting Time** and its monthly change  
4. **Average Treatment Time** and its monthly change  
5. **Average Admission Time** and its monthly change  
6. **Average Disposition Time** and its monthly change  

Other features include:
- **Monthly Trends** for each KPI across the year  
- **Total Visits by Day of the Week**  
- **Patient Distribution by**:
  - Inpatients vs Outpatients  
  - Diagnosis  
  - Outcome  
  - Tiers  
  - Nationality  

---

### **CTAS Dashboard**
The **CTAS (Canadian Triage and Acuity Scale)** dashboard dives deeper into patient acuity levels and response efficiency:

- **Total Patients and Monthly Trend**  
- **Average CTAS Time**  
- **Average Admission Time**  
- **Average Patient Satisfaction Score**  

This dashboard includes **gauge charts** to compare each CTAS level (1 to 5) against target benchmarks.  

---

### **Patient-Level Dashboard**
This dashboard provides the **lowest level of data granularity**, showing:

- `patient_id`, `date_arrived`, `triage_time`, `waiting_time`, `treatment_time`, `disposition_time`, `admission_time`
- CTAS level, doctor name, and patient satisfaction score  

This helps staff analyze performance on an individual level.  

---

## 🛠️ Skills and Techniques Used  

- **Power BI**:
  - Data cleaning and transformation using **Power Query**
  - Custom **DAX measures** for KPIs and benchmarks
  - **Time intelligence functions** for trend analysis
  - Interactive **filters** and **slicers**
  - Use of **gauge charts**, **bar charts**, and **line graphs**
  - Data Modeling to normalize the dataset
  


