# Carbohydrate Intake and Diet Quality Analysis

## Repository Structure
- `data/`: cleaned and derived datasets (raw files retained for reference)
- `cleaning/`: data preprocessing and variable construction
- `eda/`: exploratory and descriptive statistical analysis
- `modeling/`: statistical modelling and prediction
- `results/`: final analysis outputs and reporting
- `supplementary/`: additional analyses and materials

## Project Background
This project was completed as part of an interdisciplinary group coursework for  **NUTM3888 / STAT3888 – Australian Health Survey Data Analysis**  at The University of Sydney.

The project brings together students from Nutrition and Statistics backgrounds to investigate a real-world public health question using national survey data.

## Project Aim
This project aimed to examine the relationship between carbohydrate (CHO) intake, dietary fibre (DF), and blood pressure outcomes using data from the Australian Health Survey.

STAT3888 students were responsible for translating nutrition research questions into statistical problems, performing data analysis and modelling, and communicating results back to NUTM students in an interpretable way.

## Data
- Australian Health Survey (2011–2013)
  - National Nutrition and Physical Activity Survey (NNPAS)
  - National Aboriginal and Torres Strait Islander Nutrition and Physical Activity Survey (NATSINPAS)
- Final sample size: 8,546 adults after data cleaning and exclusions
- Variables included:
  - Dietary intake (carbohydrates, dietary fibre)
  - Blood pressure (systolic and diastolic)
  - Demographic and lifestyle factors (age, BMI, gender, alcohol consumption)
This project uses datasets derived from the Australian Health Survey. The raw survey files (stored under `ZipAllFiles/`) were not used directly for analysis. Instead, the analysis was conducted on cleaned and processed datasets (`.RData`), which were created through data cleaning, exclusion, and variable construction steps.

These analysis-ready datasets include dietary intake variables (e.g. carbohydrate
and dietary fibre intake), blood pressure outcomes, and relevant demographic and
lifestyle factors.

## Methodology
The analysis focused on statistical modelling and interpretability:
- Data cleaning, preprocessing, and feature construction
- Exploratory data analysis and hypothesis testing
- Correlation analysis and ANOVA
- Predictive modelling using:
  - Multiple linear regression
  - Robust regression
  - Generalised Additive Models (GAM)
- Model comparison using RMSE, MAE, and R²
- Subgroup analysis across age, BMI, gender, and alcohol consumption

## Key Findings
- Overall, associations between total carbohydrate intake and blood pressure were weak
- Dietary fibre showed modest associations with lower blood pressure in specific subgroups
- Non-linear relationships were observed between carbohydrate intake and blood pressure, particularly among younger adults and individuals with higher BMI
- GAM models provided improved predictive performance compared to linear alternatives, highlighting non-linear nutrient–health relationships

## My Contribution
This was a group coursework project completed in an interdisciplinary team.

My primary contributions included:
- Statistical analysis and modelling
- Development and comparison of predictive models (including GAM)
- Creation of data visualisations to communicate results
- Defining statistical methodology, model limitations, and assumptions
- Recording meeting notes and supporting project coordination

## Notes on Repository Structure
This repository reflects a collaborative coursework workflow.
Some notebooks represent intermediate analysis and exploration rather than polished, standalone pipelines.

The final results and methodology are documented in the project report.
