# Adelaide Rental Price Analysis – Big Data Modelling

## Project Overview
This project investigates how suburb-level attributes influence rental prices in Adelaide, South Australia. It combines official rent data with perception-based survey data to model and predict rent variations.

The work is part of the **COMP_SCI_7319OL Big Data Analysis** course and follows a full pipeline from data preparation to predictive modelling.

## Repository Contents
- **Filtered Datasets** – Pre-processed datasets used for model training and testing. These are the exact datasets on which the final results were obtained.  
- **Private Rental Reports** – Raw, unmodified datasets from the South Australian Private Rent Report (SAHT, 2025) and Adelaide Metropolitan Market Survey (City of Adelaide, 2017).  
- **Assignment_3_Code.ipynb** – The complete analysis and modelling code, executed in Google Colab.  
  - All code cells have been pre-run, with outputs already visible.  
  - No special download or configuration is required to view results.  

## Project Workflow
1. **Data Processing** – Cleaning, normalising, and merging raw datasets into analysis-ready form.  
2. **Feature Preparation** – Calculating Mean_Median_Rent and ensuring all features were compatible for modelling.  
3. **Exploratory Data Analysis (EDA)** – Generating plots to reveal rent distributions and relationships between attributes.  
4. **Predictive Modelling** – Building and evaluating Linear Regression, Ridge Regression, and Random Forest models.  
5. **Evaluation** – Random Forest achieved R² = 0.7933 and MAE ≈ 14.11.  

## How to Use This Repository
1. View the `Assignment_3_Code.ipynb` notebook in GitHub or Google Colab — all outputs are already included.  
2. Explore the `Filtered Datasets` for the processed data used in model training/testing.  
3. Check `Private Rental Reports` for the original, pre-cleaning data files. 
