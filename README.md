# UK Housing Affordability Analysis

## Project Overview

Housing affordability remains one of the most pressing economic challenges in the UK. While house prices have steadily increased, earnings have not kept pace at the same rate, creating growing pressure on households across different regions.

This project provides a data-driven analysis of housing affordability by combining the UK House Price Index (HPI) with ONS ASHE earnings data. The goal is to quantify affordability using a consistent metric and uncover how it has evolved across regions over time.

---

## Problem Statement

Organisations and policymakers often struggle to clearly measure and compare housing affordability across regions. Raw house price data alone does not provide the full picture without considering income levels.

This project addresses that gap by answering:

- How affordable is housing across UK regions?
- Which regions face the highest affordability pressure?
- How has affordability changed between 2016 and 2023?
- Are regional inequalities widening over time?

---

## Approach

The analysis follows a structured data workflow:

1. Extract and clean UK HPI and ASHE earnings datasets  
2. Standardise region names across both datasets  
3. Aggregate house prices to annual regional averages  
4. Merge datasets on region and year  
5. Calculate an **Affordability Index (House Price / Earnings)**  
6. Generate visualisations to identify patterns and trends  

---

## Dataset Preview

### UK House Price Index (HPI)
Raw dataset containing monthly house price data by region.
![HPI](outputs/dataset_preview/HPI_Dataset.png)

### HPI After Cleaning
Processed dataset with relevant fields and consistent formatting.
![HPI Clean](outputs/dataset_preview/HPI_After_Cleaning.png)

### ONS ASHE Earnings Data
Annual earnings dataset filtered for median full-time income.
![ASHE](outputs/dataset_preview/ASHE_Dataset.png)

### ASHE After Cleaning
Cleaned and structured earnings dataset.
![ASHE Clean](outputs/dataset_preview/ASHE_After_Cleaning.png)

### Merged Dataset
Final dataset combining house prices and earnings.
![Merged](outputs/dataset_preview/HPI_ASHE_Merged.png)

### Affordability Index Calculation
Illustration of how the affordability metric is derived.
![Calculation](outputs/dataset_preview/Affordability_Index_Calculation.png)

---

## Key Visual Insights

### Affordability Trend Over Time
Shows a consistent increase in affordability pressure across most UK regions.
![Trend](outputs/charts/Affordability_Index_over_time_by_region.png)

### Regional Affordability (2023)
Highlights the regions with the highest and lowest affordability levels.
![Region](outputs/charts/Affordability_Index_by_Region_2023.png)

### Affordability Heatmap (2016–2023)
Reveals how affordability has evolved spatially and temporally.
![Heatmap](outputs/charts/Affordability_Heat_Map_from_2016_2023.png)

### Affordability Change (2016 vs 2023)
Compares how affordability has shifted over time across regions.
![Comparison](outputs/charts/Affordability_Comparision_2016_2023.png)

---

## Key Findings

- London and the South East consistently experience the highest affordability pressure  
- House prices have grown significantly faster than earnings across most regions  
- The affordability gap between regions has widened over time  
- Regions that were historically affordable are now showing increasing pressure  
- The trend indicates a long-term structural imbalance between housing supply and income growth  

---

## Tools & Technologies

- **Python**  
- **Pandas & NumPy** for data manipulation  
- **Matplotlib & Plotly** for visualisation  
- **Jupyter Notebook / Google Colab** for analysis  

---

## Project Structure

housing-affordability-index-UK/
│
├── housing_affordability_analysis.ipynb
├── README.md
├── outputs/
│ ├── charts/
│ └── dataset_preview/

---

## How to Run

1. Clone the repository  
2. Install required libraries (see notebook imports)  
3. Open the notebook in Jupyter or Google Colab  
4. Run all cells to reproduce the analysis  

---

## What This Project Demonstrates

- Data cleaning and transformation of real-world datasets  
- Integration of multiple data sources  
- Time-series and regional analysis  
- Clear visual communication of insights  
- Ability to translate data into meaningful conclusions  

---

## Author

**Gaurav Parashar**  
MSc Business Analytics  
Robert Gordon University
