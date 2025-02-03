# Energy Consumption and Emissions Analysis in Calgary (2019-2023)

## Project Overview
This repository contains an analysis of energy consumption and greenhouse gas (GHG) emissions in Calgary from 2019 to 2023. The study explores trends in energy efficiency, seasonal variations, and property-type consumption patterns. Key insights are derived through data cleaning, statistical analysis, and visualization techniques.

## Repository Structure
1. data/Building_Energy_Benchmarking.csv – Raw dataset containing energy consumption and emissions data.
2. notebooks/AssignmentFour.ipynb – Jupyter Notebook with data cleaning, preprocessing, statistical analysis, and visualizations.
3. reports/Analysis_report.pdf – A detailed report summarizing key trends, efficiency metrics, and recommendations.

## How to Use This Repository
1. Open the Jupyter Notebook (AssignmentFour.ipynb ) to review the step-by-step data processing and visualization.
2. Use the PDF report (Analysis_report.pdf) for a summarized overview of key findings and recommendations.
3. If needed, analyze the raw data (Building_Energy_Benchmarking.csv) to explore additional trends.

## Data Processing & Analysis
The analysis was conducted using Python, employing the following techniques:

- Data Cleaning: Handled missing values using SimpleImputer (mean/mode), standardized postal codes, and extracted numerical values from text-based columns using Regex.
- Exploratory Data Analysis (EDA): Used pandas and groupby to identify key trends in energy consumption and efficiency.
Statistical Methods: Applied t-tests to compare mean energy usage across different property types.
- Visualizations:
  - Heatmaps & Correlation Matrices (seaborn)
  - Line Plots & Histograms (matplotlib.pyplot)
  - Summary Tables for key statistics
  - Key Insights