# New England Food Insecurity and ER Utilization Analysis

## Overview
This repository contains the analysis of the relationship between food insecurity and emergency room (ER) utilization across New England counties in 2021. The project aims to explore whether psychosocial factors, such as food insecurity, influence ER visits and average risk scores in different counties.

## Dataset
The dataset was developed with the following fields:
- **YEAR**: 2021
- **STATE**: State name
- **COUNTY**: County name
- **# FFS BENEFICIARIES**: Number of Fee-For-Service (FFS) beneficiaries
- **AVG RISK SCORE**: Average risk score for the county
- **ER VISITS PER 1000**: Emergency room visits per 1000 people
- **% FOOD INSECURE**: Percentage of the population that is food insecure, sourced from the County Health Rankings dataset

## Tools Used
- **Excel**: For data cleaning, analysis, and calculations.
- **PowerPoint**: For presenting the findings.
- **Power BI**: For data visualization.
  
## Analysis Components
### Component A
The dataset was created to include:
- average risk scores,
- ER visits per 1000, and
- food insecurity percentages for each county in New England in 2021.
  
Counties with fewer than 10,000 CMS beneficiaries were excluded from the analysis to maintain statistical relevance.

### Component B
Visual analysis was performed to determine the correlation between:
1. **Food insecurity (%) and ER utilization (ER visits per 1000)**: The analysis found a statistically significant positive relationship, with a coefficient of 0.000140392. This suggests that for every 1000 unit increase in ER visits, food insecurity in these counties increases by an average of 0.14%.

2. **Food insecurity (%) and Average Risk Score**: A positive coefficient of 0.0498 was observed, indicating that for every 1 unit increase in the average risk score, the food insecurity percentage increases by 0.0498%. However, with a p-value of 0.16, this relationship was not found to be statistically significant.

## Key Findings
### ER Utilization and Food Insecurity
- **Significant Positive Correlation**: The analysis revealed a statistically significant correlation between food insecurity and ER visits per 1000 people.
  - **Factors**:
    1. Low-income individuals facing food insecurity may delay preventative care or doctor visits to save money, leading to emergent cases later requiring costly ER utilization.
    2. States with more rural populations (e.g., ME, VT) have longer travel times to medical facilities, leading residents to utilize ERs instead of primary care.

### Average Risk Score and Food Insecurity
- **Weak Positive Correlation**: The correlation between food insecurity and average risk scores was positive but not statistically significant.
  - **Factors**:
    1. Higher food insecurity, backed by the risk of poor nutrition, stress, anxiety, and depression, worsens physical and mental health problems, increasing risk scores.
    2. States with older populations (e.g., CT, ME, VT) may have higher average risk scores since age is a key driver of risk, and risk scores tend to increase with age as chronic conditions become more common.
       
## Business Recommendations
### 1. Implement Preventative Care Programs
- Develop community-based programs targeting food-insecure populations to reduce ER visits through regular health screenings and mobile clinics.

### 2. Expand Telemedicine in Rural Areas
- Enhance access to telemedicine services in rural regions to reduce reliance on ER services by offering timely care.

### 3. Integrate Social Determinants into Risk Models
- Incorporate food insecurity and other social determinants into risk scoring models for better care management.

### 4. Partner with Local Organizations
- Collaborate with food banks and non-profits to address food insecurity, thereby improving patient health and reducing ER utilization.

### 5. Launch Chronic Disease Management Initiatives
- Focus on managing chronic conditions in food-insecure populations to prevent complications and reduce emergency care needs.

