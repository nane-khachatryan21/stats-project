# Gender Wage Gap in Armenia: Statistical Analysis Project
## Project Overview
Statistical analysis of gender wage gap in the Armenian labor market with focus on gender wage disparities across different:
- Occupations
- Regions/Settlement areas
- Educational levels

## Installation & Usage
### Setup
1. Clone repository
2. Install required packages:  
      - install.packages(c("tidyverse", "readxl", "ggplot2", "sf", "broom", "knitr", "dplyr"))

## How to Use This Repository

### **Step 1: Understand the Data**
- Methodology: [`LFS Instructions.pdf`](LFS%20Instructions.pdf)
- Survey questionnaire: [`LFS Questionnaire.pdf`](LFS%20Questionnaire.pdf)

### **Step 2: Get the Raw Data**
- Download: [`data.xlsx`](data.xlsx) *(immutable original)*

### **Step 3: Data Cleaning**
- Cleaning steps: [`data_cleaning.nb.html`](data_cleaning.nb.html)
- Cleaned output: [`cleaned_data.xlsx`](cleaned_data.xlsx)

### **Step 4: Analysis & Visualization**
- Main script: [`data_filtering.Rmd`](data_filtering.Rmd)
- Pre-run results: [`data_filtering.nb.html`](data_filtering.nb.html)
- Map data: [`armenia.json`](armenia.json)

### **Step 5: Hypothesis Testing**
- Final report: [`Report.pdf`](Report.pdf) *(full analysis & conclusions)*

---

## Project Files

| File | Description |
|------|-------------|
| [`data.xlsx`](data.xlsx) | Raw dataset (original, immutable) |
| [`cleaned_data.xlsx`](cleaned_data.xlsx) | Cleaned data output |
| [`data_cleaning.nb.html`](data_cleaning.nb.html) | Data cleaning documentation |
| [`data_filtering.Rmd`](data_filtering.Rmd) | Main analysis script (R Markdown) |
| [`data_filtering.nb.html`](data_filtering.nb.html) | Pre-run analysis output |
| [`armenia.json`](armenia.json) | Geographic map data |
| [`Report.pdf`](Report.pdf) | Final compiled report |

## Run Analysis
Execute in order:
- data_cleaning.Rmd → Generates cleaned_data.xlsx
- data_filtering.Rmd → Produces:  
    - Tables for statistical analysis
    - Visualizations (HTML reports)
