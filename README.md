# US Healthcare Data Analysis | Excel Project

<p>
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Data_Cleaning-4472C4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data_Transformation-0078D4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pivot_Tables-70AD47?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel_Formulas-217346?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/COUNTIFS-5B9BD5?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Calculated_Columns-8064A2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data_Analysis-ED7D31?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Demographic_Analysis-C55A11?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Time_Based_Analysis-4472C4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Billing_Analysis-00A6A6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Healthcare_Analytics-7030A0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Business_Insights-FFC000?style=for-the-badge"/>
</p>

## Project Overview

This project analyzes a dataset of **10,000 healthcare patient records** using Microsoft Excel. The objective is to explore patient demographics, medical conditions, hospital admissions, insurance providers, billing amounts, medications, test results, and length of stay.

The workbook demonstrates an end-to-end Excel analytics workflow, from raw data preparation and cleaning to exploratory analysis, Pivot Tables, advanced formulas, and insight generation.

> **Note:** This is a descriptive analysis of the supplied dataset. The findings describe patterns in this dataset and should not be interpreted as clinical conclusions or evidence of causation.

## Project Objectives

- Prepare and organize raw healthcare data for analysis.
- Explore patient demographics and age segments.
- Understand the distribution of medical conditions.
- Compare admission types and healthcare billing.
- Analyze insurance-provider patient volumes and billing patterns.
- Explore relationships between age groups, gender, blood types, and medical conditions.
- Examine admission timing and length-of-stay patterns.
- Translate analytical results into clear, data-backed insights.

## Dataset Description

The workbook contains **10,000 patient records** and a prepared analysis table with 25 fields.

Key fields include:

| Category | Fields |
|---|---|
| Patient details | Name, Age, Gender, Blood Type |
| Clinical information | Medical Condition, Medication, Test Results |
| Admission details | Date of Admission, Admission Type, Discharge Date |
| Hospital information | Doctor, Hospital, Room Number |
| Financial information | Insurance Provider, Billing Amount |
| Derived analysis fields | Age Bucket, Demographic Segment, Duration of Stay |
| Date dimensions | Year, Quarter, Month, Month Name, Week, Day of Admission |

## Tools & Techniques

**Tool:** Microsoft Excel

**Techniques used:**
- Data cleaning and standardization
- Data transformation and calculated columns
- Excel formulas and functions, including `COUNTIFS`, `MIN`, and percentage calculations
- Pivot Tables and Pivot-based summaries
- Demographic segmentation
- Comparative and descriptive analysis
- Conditional formatting and analytical summaries

## Workbook Structure

The Excel workbook is organized into the following sheets:

| Sheet | Purpose |
|---|---|
| `Raw Data` | Original source dataset |
| `HealthCare` | Prepared healthcare dataset |
| `Main` | Main analysis-ready dataset with derived fields |
| `Pivot Insights` | Admission-type billing analysis |
| `Sample Analysis` | Initial summaries of hospitals, conditions, and gender |
| `Advanced Analysis` | Condition, age-group, and gender analysis |
| `Advanced Analysis 2` | Blood type, insurance, and billing comparisons |
| `Insights 1` | Medical-condition analysis across demographic segments |
| `Insights 2` | Admission timing, weekly patterns, and billing analysis |

## Data Preparation & Transformation

The workbook includes a raw-data sheet and prepared analysis sheets. The prepared dataset standardizes fields such as medical-condition names and admission categories, and includes additional fields used for analysis.

Derived fields include:

- **Age Bucket:** Groups patients into Young, Middle, and Senior categories.
- **Demographic Segment:** Combines age category and gender.
- **Duration of Stay:** Calculates the difference between admission and discharge dates.
- **Year, Quarter, Month, Month Name, Week, and Day of Admission:** Supports time-based analysis.
- **Week Stays:** Groups length of stay into weekly bands.

These transformations make it easier to summarize the data and compare patient groups.

## Key Analytical Findings

The following findings are based on the prepared dataset and the Pivot Table summaries in the workbook.

### 1. Hypertension is the most frequently recorded medical condition

- Hypertension: **2,155 patients (21.55%)**
- Cancer: 1,647 patients
- Obesity: 1,627 patients
- Arthritis: 1,587 patients
- Asthma: 1,550 patients
- Diabetes: 1,434 patients


<img width="782" height="436" alt="image" src="https://github.com/user-attachments/assets/e4473e76-3bb4-4ff2-9b78-6ded59a2a2e8" />


**Insight:** Hypertension has the highest patient count among the six conditions with count of 2,155 patients, while diabetes has the lowest.

### 2. Senior patients represent the largest age group

- Senior: **3,813 patients (38.13%)**
- Middle: 3,702 patients (37.02%)
- Young: 2,485 patients (24.85%)


<img width="563" height="378" alt="image" src="https://github.com/user-attachments/assets/9aa9b73c-0cf5-45fc-b915-33550f3777cc" />


**Insight:** Senior patients form the largest age segment in the dataset, followed closely by the Middle age group.

### 3. Emergency admissions have the highest average billing amount

| Admission Type | Average Billing Amount |
|---|---:|
| Emergency | $24,279.06 |
| Elective | $23,038.95 |
| Urgent | $22,731.21 |


<img width="733" height="482" alt="image" src="https://github.com/user-attachments/assets/4b35e8c9-a8ca-49be-b64e-bc05361af71d" />


**Insight:** Emergency admissions have the highest average billing amount, approximately 3.8% above the overall average of $23,381.11.

### 4. Female patients account for a slightly larger share of records

- Female: **5,075 patients (50.75%)**
- Male: 4,925 patients (49.25%)


<img width="645" height="396" alt="image" src="https://github.com/user-attachments/assets/8f330b21-233f-4794-94af-147a2beb7cc2" />


**Insight:** The dataset has a nearly balanced gender distribution, with a small majority of female patient records.

### 5. Medicare has the highest patient count among insurance providers

| Insurance Provider | Patient Count |
|---|---:|
| Medicare | 2,428 |
| Cigna | 1,939 |
| Aetna | 1,921 |
| Blue Cross | 1,875 |
| UnitedHealthcare | 1,837 |




**Insight:** Medicare covers the largest number of patient records in this dataset, accounting for 24.28% of the total.

### 6. Cancer has the highest average billing amount

| Medical Condition | Average Billing Amount |
|---|---:|
| Cancer | $39,676.54 |
| Diabetes | $30,070.07 |
| Asthma | $22,644.61 |
| Arthritis | $20,055.06 |
| Hypertension | $17,643.29 |
| Obesity | $12,535.69 |

**Insight:** Cancer has the highest average billing amount, while obesity has the lowest. This is a descriptive comparison and does not establish why billing amounts differ.

### 7. Middle-aged and senior patients show different condition patterns

The age-group Pivot Table shows:
- Hypertension is the most frequent condition among Middle and Senior patients.
- Asthma is the most frequent condition among Young patients.
- Senior patients have the highest overall patient count.

**Insight:** The distribution of recorded medical conditions varies across age groups, making demographic segmentation useful for further investigation.

### 8. Admission volume varies across months

The monthly analysis identifies:
- October: **883 admissions**
- March: 850 admissions
- August: 845 admissions
- February: 778 admissions

**Insight:** October has the highest admission count among the months shown, while February has the lowest.

## Additional Analysis

The workbook also explores:

- Medical conditions across blood groups.
- Gender-wise distribution of medical conditions.
- Medical-condition patterns across age-and-gender segments.
- Insurance-provider billing comparisons.
- Weekly admission patterns by medical condition.
- Average billing amount across admission days.
- Length-of-stay patterns.

These additional summaries provide more detailed views of the dataset beyond the eight key findings.

## Business Recommendations

Based on the descriptive findings, the following areas may be worth investigating further:

1. **Condition-wise resource planning:** Review the higher recorded volume of hypertension cases when evaluating staffing and service requirements.
2. **Senior-patient services:** Explore whether the larger senior-patient segment requires additional age-focused service planning.
3. **Emergency billing review:** Investigate the factors associated with higher average emergency billing.
4. **Insurance analysis:** Compare provider-level billing and patient volumes to better understand differences across insurance groups.
5. **Monthly capacity planning:** Review monthly admission patterns when planning operational capacity.
6. **Length-of-stay monitoring:** Use the calculated stay duration to investigate unusually long or short hospital stays.

## Skills Demonstrated

- Microsoft Excel
- Data Cleaning
- Data Preparation
- Data Transformation
- Pivot Tables
- Advanced Excel Formulas
- `COUNTIFS` and conditional calculations
- Demographic Analysis
- Healthcare Data Analysis
- Billing Analysis
- Exploratory Data Analysis (EDA)
- Business Insight Generation

## Project File

The repository includes the Excel workbook:

`Complete US HealthCare Project.xlsx`

Open the workbook in Microsoft Excel to explore the raw data, prepared dataset, Pivot Tables, calculations, and analysis sheets.

## Conclusion

This project demonstrates how Microsoft Excel can be used to transform raw healthcare records into structured information and meaningful analytical insights.

By combining data preparation, calculated fields, Pivot Tables, and comparative analysis, the project explores patient demographics, medical conditions, admission patterns, insurance providers, and billing trends.

---

**If you find this project useful, feel free to star the repository!**
