# Loblaw
Loblaw Health Division – Data Analytics Project

📌 Project Overview
This project focuses on leveraging patient-level healthcare data to identify individuals at risk of becoming high-cost cases and to recommend early interventions through Loblaw's operational channels — such as pharmacy, virtual care, and biometric programs.

By integrating and analyzing medical records, biometric indicators, and demographic data, this project delivers actionable insights and a Power BI dashboard designed to support strategic decision-making in population health management.

🎯 Objective
How can Loblaw use its existing patient data to identify high-risk individuals before their costs escalate — and intervene early using its retail health ecosystem?

🔍 Business Problem
Loblaw is expanding its role in healthcare, with significant investments in pharmacy, digital health platforms, and chronic disease management. However, without being a direct payer in the healthcare system, its challenge lies in:

Reducing downstream costs

Enhancing service utilization

Driving value from patient engagement data

🧠 Key Insights from Data
Cost Concentration

Top 20% of patients contribute to nearly 70% of total medical costs — highlighting a small, high-cost population.

Diagnosis Frequency

Hypertension, Type 2 Diabetes, and Asthma are the most frequent diagnoses — all manageable through pharmacy interventions.

Biometric Red Flags

30% of patients have BMI > 30 or BP > 140/90 — indicating unmanaged chronic risk.

Age & Risk Correlation

Risk and cost increase significantly after age 50 — priority age group: 50–75.

🛠️ Tools & Technologies
Category	Tools Used
Programming	Python (Pandas, Matplotlib, Seaborn)
Data Visualization	Power BI
Data Management	Jupyter Notebooks, CSV files
Analytics Workflow	EDA, Risk Scoring, Stratification
Dashboarding	Interactive Power BI report

🧩 Dataset Overview
patients.csv – Demographic information (age, gender, ethnicity, zip code)

medical_records.csv – Diagnoses, visit types, costs, and physician data

biometrics.csv – Blood pressure, BMI, cholesterol, glucose levels

🧪 Methodology
Data Cleaning & Preprocessing
Removed nulls, standardized column names, joined datasets on patient ID.

Exploratory Data Analysis (EDA)
Identified correlations between biometric values, cost, and diagnosis frequency.

Risk Stratification
Defined flags for chronic disease and biometric thresholds to segment patient risk.

Power BI Dashboard
Designed an interactive dashboard to allow stakeholders to explore risk by age, cost, diagnosis, and visit type.

📈 Strategic Recommendations
Initiative	Description
Targeted Pharmacy Outreach	Focus on patients with chronic conditions + high BMI/BP
Preventive Screening Programs	Expand checkups for age 50–75 based on rising risk
Telehealth Adoption Incentives	Shift moderate/high-risk patients to lower-cost visit types

📊 Dashboard Preview
Embedded dashboard or screenshots go here (Power BI)

🧾 Files Included
File Name	Description
Data Cleaning and Preprocessing.ipynb	Cleans and merges datasets
Exploratory Data Analysis.ipynb	Descriptive stats, trends, visualizations
Risk Factor Insights.ipynb	Biometric segmentation, risk classification
Merging Health Care Data Set.ipynb	Final data model used for dashboard

💬 Conclusion
This project demonstrates how healthcare analytics can inform business strategy. By identifying high-risk patient segments early, Loblaw can enhance care outcomes while improving retail health economics — aligning clinical insight with commercial value.

