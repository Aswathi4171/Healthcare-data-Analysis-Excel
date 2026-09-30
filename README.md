# Healthcare-data-Analysis-Excel
# 🏥 Healthcare Data Analysis and Insights

## 📌 Project Overview

This project focuses on analyzing healthcare data using **Microsoft Excel** to identify useful insights related to patient health, medical history, hospital information, and healthcare charges.

The project includes data cleaning, data transformation, data exploration, analysis, visualization, and an interactive dashboard.

## 🎯 Objectives

- Clean and prepare the healthcare dataset
- Handle missing values
- Transform and standardize the data
- Combine multiple healthcare tables using VLOOKUP
- Analyze healthcare charges and patient health conditions
- Create PivotTables and visualizations
- Build an interactive healthcare dashboard

## 📂 Dataset

The project contains three main tables:

- **Customer Names**
- **Medical Examinations**
- **Hospitalisation Details**

The tables are combined using **Customer ID** as the common field.

## 🧹 Data Cleaning

The following data-cleaning tasks were performed:

- Identified missing values marked with `?`
- Filled missing month values with **Sep**
- Filled missing year values using the rounded average year
- Filled missing Hospital Tier and City Tier values using the most frequent values
- Handled missing State ID values using **Unknown**

## 🔄 Data Transformation

The following transformations were performed:

- Split customer names into:
  - Title
  - First Name
  - Last Name
- Converted NumberOfMajorSurgeries into numerical values
- Checked Heart Issues and smoker columns for inconsistencies
- Created **Weight Status** based on BMI:
  - Underweight
  - Normal Weight
  - Overweight
  - Obesity
- Created **Diabetes Status** based on HbA1C:
  - Normal
  - Prediabetes
  - Diabetes
- Created Date of Birth from Year, Month, and Date
- Calculated customer Age based on **8-Jun-2023**
- Formatted healthcare charges as currency

## 📊 Data Analysis

The project includes the following analyses:

### 1. Cancer History Among Smokers and Non-Smokers
A PivotTable and chart were created to analyze the distribution of cancer history among smokers and non-smokers.

### 2. Major Surgeries and HbA1C by Transplant Status
The analysis compares:

- Total number of major surgeries
- Average HbA1C

for patients with and without a history of transplants.

### 3. Healthcare Charges by Weight and Diabetes Status
Healthcare charges were analyzed across different:

- Weight Status categories
- Diabetes Status categories

### 4. Average Charges by Hospital Tier and State
Average healthcare charges were compared across hospital tiers within different states.

### 5. Age, BMI and HbA1C
Scatter plots were created to explore relationships between:

- Age and BMI
- Age and HbA1C

### 6. Age vs Healthcare Charges
A scatter plot was created to explore the relationship between age and healthcare charges.

## 📈 Dashboard

An interactive **Healthcare Data Analysis Dashboard** was created using the above visualizations.

The dashboard includes:

- Charts and visualizations
- Weight Status slicer
- Diabetes Status slicer
- Healthcare charge analysis
- Patient health analysis

## 🛠️ Tools Used

- **Microsoft Excel**
- PivotTables
- VLOOKUP
- Excel Formulas
- Charts
- Slicers
- Dashboard

## 📁 Project Files

- `main assignment-1.xlsx` — Completed Excel project
- `README.md` — Project documentation

