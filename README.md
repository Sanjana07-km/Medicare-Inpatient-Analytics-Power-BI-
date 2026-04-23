# Medicare-Inpatient-Analytics-Power-BI-
An end-to-end healthcare analytics dashboard built using CMS Medicare Inpatient Program Statistics data (2023), covering 50 US states across 4 analytical dimensions.
# Medicare Inpatient Hospital Analytics Dashboard
### Power BI | CMS Program Statistics | 2023

## Project Overview
An end-to-end healthcare analytics dashboard built using CMS Medicare Inpatient Program Statistics data (2023), covering 50 US states across 4 analytical dimensions.

## Business Problem
Analysed Medicare inpatient hospital utilisation and payment trends to identify cost drivers, state-level discharge patterns, patient demographics, and hospital type efficiency — simulating real-world payor analytics work.

## Dashboard Pages
| Page | Focus | Key Visual |
|------|-------|------------|
| Overview | National trends 2018–2023 | Line chart showing COVID discharge dip |
| State Map | Geographic utilisation | Filled US map by discharge rate |
| Demographics | Patient profile | Age, sex, race breakdown |
| Hospital Analysis | Cost by hospital type | Bar chart comparison |

## Key Insights
- Total Medicare discharges: ~8M (2023)
- Avg payment per discharge: ~$16K
- Discharges dropped 12% in 2020 (COVID) but avg payment rose 8%
- Patient cost burden: 6.9% of total payments
- Florida, California, Texas — highest discharge volumes

## Technical Skills Demonstrated
- **Power Query (M Code)**: Cleaned 5 tables — removed title rows, filtered junk rows, fixed data types, added calculated columns (Beneficiary Type, Category)
- **DAX Measures**: DIVIDE, SUM, AVERAGE, IF, VAR/RETURN, CALCULATE
- **Data Modelling**: 5-table model, measures table, geographic data categories
- **Visualisations**: KPI cards, line charts, filled map, bar charts, slicers, conditional formatting

## Data Source
CMS Program Statistics — Medicare Inpatient Hospital 2023  
Source: [data.cms.gov](https://data.cms.gov)

## Tools Used
- Microsoft Power BI Desktop
- Microsoft Excel
- Power Query (M Code)
- DAX
