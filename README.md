# COVID-19_Impact_on_Digital_Learning

This project analyses the **impact of COVID-19 on digital learning engagement** using district-level and product-level data from the United States. It was completed as part of an academic assessment to apply **data cleaning, wrangling, and exploratory analysis** in R.

## Overview
The dataset covers multiple school districts and digital learning products, with engagement metrics collected during the COVID-19 pandemic. The goal is to understand:
- How engagement varied across states and products
- The relationship between district characteristics and digital learning usage
- The broader implications of remote learning adoption during school closures

## Dataset
- **Engagement Data** – CSV files (`1000.csv`, `1039.csv`, `1044.csv`, `1052.csv`, `1131.csv`) containing daily engagement metrics for different districts.
- **Districts Info** – Demographics and socio-economic indicators for each district (`districts_info.csv`).
- **Products Info** – Metadata about digital learning products (`products_info.csv`).

## Workflow
1. **Data Cleaning & Wrangling**
   - Correcting state name inconsistencies
   - Handling missing values and erroneous entries
   - Standardising categorical variables
2. **Merging Datasets**
   - Joining engagement data with district and product information
3. **Exploratory Data Analysis (EDA)**
   - Trends in engagement during the pandemic
   - Product adoption rates by state and district type
   - Relationship between socio-economic status and engagement
4. **Insights & Interpretation**
   - Highlighting patterns in remote learning behaviour
   - Identifying disparities in digital learning access

## Tools
- **R** – `tidyverse`, `readr`, `dplyr`, `ggplot2`
- **R Markdown** for documentation and reporting

## Purpose
To evaluate the **educational technology usage patterns** during COVID-19 and identify actionable insights that can guide **future digital learning strategies**.

---
**Author**: Muhammad Pasha Arrighi Effendi  
