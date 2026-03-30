# Assignment 2 – Explaining the COMPAS Replacement Model

**Name:** Rafay Raza  
**GWID:** G40856805

## Purpose of the Analysis
The purpose of this analysis is to build a COMPAS replacement risk prediction model and apply explainability methods to understand how the model makes decisions. Two models were trained: a logistic regression model and a gradient-boosted tree model. Explainability techniques including SHAP, LIME, and counterfactual explanations were used to interpret model predictions. Fairness was evaluated by comparing error rates such as false positive rate and false negative rate across racial groups.

## Python Libraries Used
The following Python libraries were used in this assignment:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn
- lime
- shap
- dice-ml

## Instructions for Reproducing the Results
To reproduce the results:

1. Install the required Python libraries:
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn lime shap dice-ml

2. Open the Jupyter Notebook file:
   RafayRaza_Assignment_2.ipynb

3. Run all cells in the notebook from top to bottom.  
   The notebook will:
   - Load and clean the COMPAS dataset
   - Train logistic regression and gradient boosted models
   - Evaluate fairness metrics across racial groups
   - Generate SHAP explanations
   - Generate LIME explanations
   - Generate counterfactual explanations
   - Produce governance analysis
  
The dataset is loaded directly from the ProPublica COMPAS dataset repository:
https://raw.githubusercontent.com/propublica/compas-analysis/master/compas-scores-two-years.csv

## AI Acknowledgment
AI tools were used for general programming guidance, debugging, and assistance with Markdown formatting and grammar.
