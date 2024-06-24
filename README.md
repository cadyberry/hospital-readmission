
# Predicting Early Patient Readmission

## Overview

This study analyzes over 101,000 hospital records from the Cerner Health Facts Database spanning 10 years (1999-2008) across 54 US hospitals to investigate the relationship between comorbidities, hospital care markers, and early readmission rates in diabetic patients. Using multivariable logistic regression, XGBoost, random forest, and support vector machines, the research explores the impact of significant variables on readmission. It builds on prior findings linking hemoglobin A1c measurement during patient encounters to lower readmission rates, aiming to enhance interventions and patient care strategies through data preparation, exploratory analysis, and statistical modeling. The study addresses challenges in heterogeneous clinical data, contributing to healthcare outcomes and cost reduction efforts for diabetic patients.

## Instructions

To run this project, follow these steps:

1. **Download the Dataset:**
   - To download the dataset `diabetic_data.csv`, click [here](https://github.com/cadyberry/hospital-readmission/blob/main/diabetic_data.csv).

3. **Run Files in Order:**
   - Run the following files in sequence:
     1. `1- Data prep.rmd`: Data cleaning and preparation.
     2. `2- EDA.rmd`: Exploratory data analysis.
     3. `3- Modeling.rmd`: For modeling and model metrics

## Usage

### Step 1: Download Dataset

Download the dataset `diabetic_data.csv`[here](https://github.com/cadyberry/hospital-readmission/blob/main/diabetic_data.csv).

### Step 2: Run Files

Ensure R is installed. Run the RMD files in order:

     1. `1- Data prep.rmd`: Data cleaning and preparation.
     2. `2- EDA.rmd`: Exploratory data analysis.
     3. `3- Modeling.rmd`: Modeling and model metrics

## Dataset

This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. Access to this data is permitted under the condition that proper citations are provided. The URL to access the data is:  (https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008).
