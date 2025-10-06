# Wage Data Analysis using Clustering, Classification, and Regression

## Overview
This project analyzes wage data from Poland’s **Central Statistical Office (GUS)**, sourced from the **Structure of Wages and Salaries by Occupations (SWS)** database (October 2010).  
The goal was to explore relationships between employee characteristics and salaries using data science methods, including **exploratory data analysis**, **clustering**, **classification**, and **regression**.

## Dataset
The dataset contains anonymized employee-level data from non-financial entities with more than nine employees.  
Key variables include:
- **Base salary**, **bonus**, **overtime pay**, and **other remuneration**
- **Sector** (public/private), **industry section**, **sex**, **education**, and **contract type**
- **Age** and various **employment duration** measures

## Methodology

### 1. Data Exploration
- Loaded and cleaned the dataset, handling missing and categorical values.
- Conducted descriptive analysis and visualized distributions of key variables.
- Compared salary distributions across sectors, education levels, and gender.

### 2. Clustering
- Applied unsupervised learning to group employees based on salary components and work characteristics.
- Scaled variables appropriately and determined the optimal number of clusters using the silhouette score.

### 3. Classification
- Built models to predict whether an employee holds a higher education degree based on other features.
- Evaluated multiple algorithms using cross-validation.
- Analyzed feature importance to identify factors correlated with education level.

### 4. Regression
- Developed regression models to **predict base salary**.
- Used feature selection to improve interpretability and performance.
- Discussed the positive or negative impact of each variable on predicted salary.

## Author
Project completed as part of the **Wage Data Analysis lab (WUM)** — April 2025.
