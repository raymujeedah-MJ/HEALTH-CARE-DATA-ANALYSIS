# HEALTH-CARE-DATA-ANALYSIS
This project explores a healthcare dataset using Microsoft Excel. The workbook covers data preparation, PivotTable analysis, KPI summaries, and  interactive dashboard

The analysis uses 150 patient records and focuses on patient demographics, medical conditions, admission types, medications, insurance providers, billing amounts, and test results.
Dashboard Preview

## Tools Used

- Microsoft Excel
- Excel Tables and data-cleaning features
- PivotTables and PivotCharts
- Excel formulas and KPI summaries
- Dashboard visualisation and slicers (where included in the workbook)

## Workbook Contents

All project work is contained in [`Healthcare_Data_Analysis.xlsx`](Healthcare_Data_Analysis.xlsx). The workbook includes these sheets:

| Sheet | Description |
|---|---|
| Dataset information | Description of the dataset and its fields |
| Healthcare Dataset | Original dataset |
| Cleaned Dataset | Prepared dataset used for analysis |
| PivotTable | PivotTable summaries answering the analysis questions |
| KPIs | Key performance indicators and summary metrics |
| Dashboard | Hospital management analysis dashboard |
| INSIGHTS | Findings, limitations, and recommendations |

## Questions Explored

- Which age group has the highest number of patients?
- What is the gender distribution of admissions?
- Which medical conditions occur most frequently?
- Which admission type is most common?
- Which medications are prescribed most often?
- Which insurance providers are most represented?
- What is the distribution of test results?
- Which blood types are most common?
- What are the overall patient and billing KPIs?

## Selected Findings

Based on the workbook's PivotTables and KPI summary:

- Total patient records analysed: **150**
- Total billing amount: **3,784,431.38** (currency not specified in the workbook)
- Average billing amount: **25,229.54**
- Average patient age: **48.7 years**
- Number of insurance providers represented: **5**
- The most represented age group is **Senior** (59 patients).
- Female admissions: **74**; male admissions: **76**.
- Hypertension and Cancer are tied as the most frequent medical conditions (29 records each).
- Ibuprofen is the most frequently listed medication (37 records).

These are descriptive findings from this dataset; they should not be interpreted as clinical conclusions or representative of a real hospital population.

## Data Quality and Limitations

The project documentation in the workbook records the following limitations:

- Hospital and Doctor fields contain unique values for each patient, limiting useful comparisons across those fields.
- Admission and discharge dates contain inconsistencies that result in negative lengths of stay for some records. Length-of-stay analysis was therefore excluded from the dashboard.
- The dataset appears to be synthetically generated for learning purposes, which limits real-world operational conclusions.
