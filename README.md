# Mental Health Risk Analysis (Household Pulse Survey)

This project analyzes publicly available indicators of anxiety and depression from the U.S. Census Bureau’s Household Pulse Survey.  
The study identifies which demographic groups experience the highest levels of depressive symptoms and evaluates whether such high-risk groups can be predicted using a simple classification model.

## Research Goals
- Identify demographic subgroups with elevated depressive symptom rates  
- Test hypotheses based on existing psychological and epidemiological research  
- Build a logistic regression model predicting whether a subgroup is “high-risk”  
- Critically reflect on model limitations in the context of mental health data  

## Methods
The analysis follows a two-step PPDAC-inspired approach:

1. **Exploratory Data Analysis (EDA)**  
   - Group comparisons (age, gender, education)  
   - Visualizations and descriptive metrics  
   - Evaluation of hypotheses H1–H3  

2. **Classification Model**  
   - Binary target (“HighRisk”) based on a median split
   - Logistic regression using demographic predictors  
   - Evaluation with Accuracy, F1-score and confusion matrix  

## Contents
- `Doerr-MentalHealth.ipynb`: full analysis notebook

## Data Source
- U.S. Census Bureau, Household Pulse Survey  
- Indicators of Anxiety or Depression (Monfared, 2022)

## Disclaimer
The model is intended for educational purposes only and does not support individual diagnosis.
