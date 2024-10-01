# Diabetes Bayesian Analysis

## Table of Contents
1. [Overview](#overview)
2. [Key Findings](#key-findings)
3. [Data Description](#data-description)
4. [Methodology](#methodology) 
5. [Visualizations](#visualizations)
6. [Conclusion](#conclusion)

## Overview
This project uses Bayesian analysis to investigate the differences in various health parameters between individuals with diabetes and those without. We utilize Monte Carlo simulations to estimate the parameters for both groups and visualize the results to highlight the differences.

## Key Findings
- **Significant Differences**: Parameters such as the number of pregnancies, skin fold thickness, BMI, blood pressure, age, and glucose levels show notable differences between individuals with and without diabetes.
- **Parameter Distributions**: The density plots reveal the distributions of these parameters, allowing for a visual comparison between the two groups.

## Data Description
The dataset includes health-related variables for patients, specifically focusing on:
- **Number of Pregnancies (npreg)**
- **Skin Fold Thickness (skin)**
- **Body Mass Index (BMI)**
- **Blood Pressure (bp)**
- **Age (age)**
- **Glucose Levels (glu)**
- **Diabetes Status (diabetes)**: Indicates whether the patient has diabetes ("Yes" or "No").

## Methodology
1. **Data Preparation**: The dataset is divided into two groups based on diabetes status: those with diabetes and those without.
2. **Monte Carlo Simulations**: We perform simulations to estimate the means and covariance structures for both groups using prior distributions.
3. **Parameter Estimation**: The estimated parameters are stored for further analysis and visualization.
4. **Visualizations**: Density plots are generated to compare the distributions of key health parameters between the two groups.

## Visualizations
The following plots are included:
- **Number of Pregnancies**: Comparison of distributions for individuals with and without diabetes.
- **Skin Fold Thickness**: Visual representation of differences in skin fold thickness.
- **BMI**: Density plots illustrating BMI distributions.
- **Blood Pressure**: Comparison of blood pressure levels.
- **Age**: Age distribution comparison.
- **Glucose Levels**: Differences in glucose levels between the two groups.

## Conclusion
This analysis highlights the significant health differences between individuals with diabetes and those without, providing insights that could be valuable for healthcare professionals and researchers in understanding diabetes-related health impacts.
