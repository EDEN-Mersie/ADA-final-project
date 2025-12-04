# ADA Final Project – Health Insurance Coverage and Seasonal Influenza Vaccination
Among U.S. Adults Aged 18–64 (BRFSS 2024)

## Project Description
This repository contains data and R code for my Applied Data Analysis (ADA) final project. The project uses 2024 BRFSS data to examine whether having any health insurance coverage is associated with receiving an influenza vaccine in the past 12 months among U.S. adults aged 18–64, and whether this association differs by household income.

## Files Included
- `final project ADA code.Rmd`: Main R Markdown file for data cleaning, multiple imputation, and analysis
- `README.md`: This file
- `LLCP2024.XPT`:dataset 

## What the Code Does
- Imports and subsets BRFSS 2024 data (adults 18–64 in 50 states + DC)  
- Selects key variables: flu shot, insurance status, age, sex, household income, state  
- Examines missing data patterns and uses MICE for multiple imputation  
- Creates descriptive Table 1 by insurance status  
- Fits univariate and multivariable logistic regression models (flu shot vs insurance)  
- Tests effect modification by income using an insurance × income interaction  
- Produces model diagnostics, predicted probability plots, and ROC curves

## How to Run the Code
1. Download or clone this repository to your computer  
2. Open `final project ADA code.Rmd` in RStudio  
3. Make sure your working directory is set to the project folder  
4. Knit or run the R Markdown file from top to bottom  

## Author
- Name: Eden Mersiehazen  
- Course: Applied Data Analysis (ADA)  
- Date: 12/2025