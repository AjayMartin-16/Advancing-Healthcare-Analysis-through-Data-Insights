# Advancing Healthcare Analysis Using Power BI  

## Objective  
This project leverages **Power BI** to conduct an in-depth analysis of healthcare data, focusing on **data cleaning, modeling, and advanced analytics using DAX**. The goal is to create an **interactive dashboard** that provides **actionable insights** for healthcare providers, enhancing **patient care** and **operational efficiency**. This analysis helps position **HealthStat Solutions** as a leader in healthcare analytics.  

![image](https://github.com/user-attachments/assets/6c574313-fc1d-4932-915d-34aa46bbb61f)
  

[Check out the Power BI file here](https://drive.google.com/file/d/1iSty2xRxsL4sNf7QjXm65IuJ-ahm7Bc-/view?usp=sharing)  

---  

## Data Sources  
- **Patient Data:** Includes Patient ID, name, age, and other demographic details.  
- **Hospital Data:** Contains details of various hospitals and their facilities.  

## Analysis Workflow  

### **Part 1: Data Cleaning, Modeling & DAX Analysis**  

1. **Data Import & Quality Check**  
   - Imported datasets into **Power BI** and identified inconsistencies.  
   - Addressed missing values, duplicates, and irrelevant data.  

2. **Merging & Data Transformation**  
   - Combined datasets using a common key to ensure completeness.  
   - Converted **AdmissionDate** and **DischargeDate** into appropriate formats.  

3. **Feature Engineering**  
   - Created **Age Groups** (Child, Adult, Senior) to analyze patient distribution.  
   - Computed **Length of Stay** for each patient.  
   - Derived **Total Treatment Cost** using 'TotalBill' and 'DailyCost'.  

4. **Key Analytical Insights**  
   - **Gender vs. Diagnosis:** Identified patterns in disease occurrence among different genders.  
   - **Blood Type Distribution:** Analyzed the prevalence of each blood type.  
   - **Recovery Rating by Treatment Type:** Used **DAX** to determine which treatments yield better recovery rates.  
   - **Hospital Utilization:** Evaluated **average patients per room** to assess hospital capacity.  
   - **Doctor’s Patient Load:** Compared the number of patients treated by doctors and its correlation with recovery ratings.  
   - **Treatment Effectiveness:** Analyzed **length of stay vs. recovery rating** to determine the most effective treatments.  

### **Part 2: Building an Interactive Dashboard**  

- Designed a **Power BI dashboard** featuring:  
  - **Patient Demographics** (Age groups, Gender distribution)  
  - **Diagnosis & Treatment Insights** (Most common diseases, highest-cost treatments)  
  - **Recovery & Hospital Metrics** (Hospital occupancy, doctor workloads)  
  - **Filters for deeper analysis** (Hospital, diagnosis, treatment type)  

---  

## **Key Findings & Business Insights**  

**High-cost treatments:** Certain procedures showed significantly **higher average costs**, indicating a need for **cost control strategies**.  
**Gender-based diagnosis trends:** Some illnesses were more prevalent in **specific gender groups**, which can help in **targeted preventive care**.  
**Age-related recovery rates:** Seniors had **longer hospital stays**, emphasizing the need for **personalized elderly care**.  
**Hospital efficiency:** Some hospitals had **higher patient-to-room ratios**, pointing to **capacity planning needs**.  
**Doctor workload & recovery:** Overloaded doctors had
