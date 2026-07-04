# powerBI-healthcare-appointment-operations-dashboard
Power BI dashboard project analyzing healthcare appointment volume, provider workload, and waiting time trends.

# Healthcare Appointment Operations Dashboard

## Project Overview

This project is a Power BI dashboard analyzing healthcare appointment operations using a public appointment scheduling dataset. The goal of this project is to evaluate appointment volume, provider workload, and patient waiting time in order to identify operational patterns and provide business recommendations.

This project was created as part of my Data Analyst portfolio to demonstrate skills in data analysis, KPI design, dashboard development, operational reporting, and data storytelling.

## Business Problem

Healthcare organizations need to monitor appointment volume, provider workload, and waiting time in order to improve scheduling efficiency and patient access. This dashboard helps answer the following questions:

- How many appointments and patients are included in the dataset?
- What is the average waiting time?
- Which provider roles handle the most appointments?
- Which provider roles have the longest average waiting time?
- Are appointment volumes stable over time?
- Are there any unusually long waiting times that may indicate scheduling bottlenecks?

## Dataset

This project uses the **Appointment Scheduling Dataset** from Kaggle.

**Original Dataset**
- **Dataset Name:** Healthcare Appointment Data - Power BI Project
- **Source:** Kaggle
- **Link:** https://www.kaggle.com/datasets/swsw1717/healthcare-appointment-power-bi-project

To support dashboard development and operational analysis, the original dataset was cleaned and transformed before visualization.

### Data Preparation

The following preprocessing steps were performed:

- Cleaned and standardized the dataset for analysis.
- Converted the original **Waiting Time** text field into numeric values.
- Added two engineered features:
  - **Waiting Time Days**
  - **Waiting Time Hours**
- Used the cleaned dataset as the data source for all Power BI visualizations.

No original business records were removed or altered beyond data cleaning and feature engineering.


## Dashboard Pages

### Page 1: Executive Dashboard

The first page provides a high-level overview of appointment operations, including:

- Total Appointments
- Unique Patients
- Average Waiting Time
- Provider Roles
- Appointments Over Time
- Appointments by Provider Role
- Provider Role Filter

### Page 2: Healthcare Appointment Analysis

The second page focuses on deeper operational analysis, including:

- Average Waiting Time by Provider Role
- Average Waiting Time Over Time
- Waiting Time Summary Table
- Key Findings
- Recommendations

## Key Findings

1. The dashboard includes 99 appointments and 99 unique patients.
2. The overall average waiting time is 10.55 days.
3. Psychologist appointments have the highest average waiting time, followed by Nurse and MD.
4. MD has the highest appointment volume.
5. Appointment volume is generally stable, with only a few dates showing multiple appointments.
6. Several appointments have waiting times over 30 days, which may indicate potential scheduling bottlenecks.

## Recommendations

1. Review scheduling processes for Psychology appointments to reduce waiting time.
2. Monitor MD workload because MD handles the largest appointment volume.
3. Investigate appointments with waiting times over 30 days to identify scheduling bottlenecks.
4. Track waiting time trends regularly to support operational planning.

## Tools Used

- Microsoft Power BI
- Power BI Service
- Power Query / Data Cleaning
- Data Visualization
- Dashboard Design
- Business Analysis

## Files Included

- `healthcare_appointment_operations_dashboard.pbix` - Power BI dashboard file
- `healthcare_appointment_operations_dashboard.pdf` - exported dashboard preview
- `Appointment Scheduling Cleaned Data.csv` - cleaned dataset used for the dashboard

## Skills Demonstrated

- KPI design
- Operational analysis
- Healthcare appointment analysis
- Provider workload analysis
- Waiting time analysis
- Interactive dashboard design
- Business insights and recommendations
- Data storytelling
