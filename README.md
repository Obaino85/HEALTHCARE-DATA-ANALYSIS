# HEALTHCARE-DATA-ANALYSIS
This project involves analyzing healthcare data to gain insights that can improve patient care, optimize hospital operations, and support healthcare decision-making. The dataset includes information about patient demographics, medical conditions, blood type, and medication.

## Project Objectives

- **Understand Patient Demographics and Health Trends**  
  Analyze patient characteristics such as age, gender, location, and medical history to understand trends in health conditions, risk factors, and treatment patterns.

- **Monitor Healthcare Operations**  
  Analyze hospital operations, including patient admissions, discharge dates, waiting periods, and resource utilization, to optimize workflows and reduce delays.

- **Predict Patient Outcomes**  
  Develop predictive models to forecast patient outcomes such as recovery time, risk of complications, or hospital readmission based on historical data.

## Data Cleaning Process

- **Missing Values Handling**  
  Identified missing data in key fields such as `Diagnosis`, `PatientAge`, and `AdmissionDate`. Used imputation techniques (mean, median, forward fill) or dropped rows/columns with excessive missing data.

- **Data Type Conversions**  
  Converted date fields (e.g., `AdmissionDate`, `DischargeDate`) to proper datetime formats.  
  Ensured numeric fields like `Age`, And `BloodType` were appropriately typed as numeric.

- **Duplicate Removal**  
  Checked for and removed duplicate patient records or treatment logs based on `PatientID` and `Discharge ID` to ensure accuracy and avoid double-counting.

- **Standardization**  
  Standardized medical terms, diagnosis codes (e.g., ICD codes), and treatment methods to ensure consistency across the dataset.  
  Ensured uniformity in measurement units, such as weight in kilograms and height in centimeters.

- **Outlier Detection**  
  Applied statistical methods (e.g., Z-score, IQR) to detect extreme outliers in clinical data like `Age`, `BloodPressure`, `MedicationDosage`, and flagged them for review.


