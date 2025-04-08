# Investigating the prevalance of metabolic syndrome

This repository contains resources for the project "Investigating Prevalence of Metabolic Syndrome", which examines the relationships between demographic and health factors and their influence on the prevalence of metabolic syndrome. Leveraging robust statistical techniques, the project provides insights to inform prevention and intervention strategies for metabolic syndrome.

## Project Overview
- **Objective**: Investigate the associations between demographic factors (age, sex, race) and health variables (BMI, blood glucose, uric acid, HDL cholesterol) with metabolic syndrome prevalence. Identify the most influential factors among individuals with specific risk profiles.
- **Data Source**:[Metabolic syndrome Dataset](https://www.kaggle.com/datasets/antimoni/metabolic-syndrome)
- **Approach**:
  - Explored variable distributions and relationships through visualizations.
  - Performed statistical analyses, including chi-square tests and logistic regression.
  - Addressed non-normal data distributions using non-parametric techniques.
  - Identified key predictors and quantified their effects.
- **Results**: BMI emerged as the strongest predictor among health factors, while race (Mexican American) was the most significant demographic determinant.
  
## Files in the repository

- `metabolic-syndrome-analysis.Rmd`: R Markdown file containing code for data cleaning, statistical analyses, and visualizations.
- `metabolic-syndrome-project-report.pdf`: Detailed report outlining the study's objectives, methodology, findings, and conclusions.
- `metabolic-syndrome-presentation.pdf`: Slide deck summarizing the project, including key findings and implications.

## Methodology

1. **Data Preprocessing**:
    - Addressed missing values (<1%) by removing rows with null entries in the BMI column.
    - Detected and treated outliers in BMI, blood glucose, uric acid, and HDL using capping techniques.
2. **Descriptive Statistics**:
   - Summarized central tendency and variability metrics for key variables.
   - Assessed participant demographics and health factor distributions.
3. **Statistical Analysis**:
   - Normality Assessment:
     - Shapiro-Wilk test confirmed non-normal distributions across variables.
   - Chi-Square Test:
     - Investigated associations between categorical variables and metabolic syndrome prevalence.
   - Logistic Regression:
     - Modeled the likelihood of metabolic syndrome occurrence.
     - Quantified the influence of age, BMI, blood glucose, HDL, and uric acid on metabolic syndrome prevalence.
   - Multiple Logistic Regression:
     - Determined the strongest demographic and health predictors.
4. **Visualization**:
   - Created boxplots, histograms, and correlation heatmaps to explore variable trends and relationships.
     
## Key Findings
- BMI: The strongest health predictor of metabolic syndrome prevalence.
- Race: Individuals of Mexican American descent exhibited the highest risk among demographic groups.
- Age: Increasing age significantly elevated the odds of metabolic syndrome.
- HDL Levels: Low HDL cholesterol levels were strongly associated with metabolic syndrome.
  
## Limitations
- Logistic regression assumes linearity and independence, which may not hold in complex datasets.
- Sample size limitations within certain demographic categories could affect generalizability.

## Applications
- Healthcare Providers: Tailor interventions to address significant risk factors like BMI and glucose levels.
- Public Health: Develop targeted initiatives for at-risk populations, such as Mexican American individuals.

## Contributors
- Asha Chirumamilla
- Likhitha Arigala
- Pallavi Telu
- Teja Pavani Jyesta
- William Teske

## Contact
For questions or suggestions, please contact:  
Pallavi Telu - [ptelu@iu.edu](mailto:ptelu@iu.edu)


