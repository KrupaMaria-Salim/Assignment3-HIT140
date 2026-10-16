# FIFA World Cup 2026 – Goal Prediction Using Linear Regression

# Foundations of Data Science – Assessment 3

Charles Darwin University | Semester 2, 2026

# Project Overview

This group project focuses on predicting FIFA World Cup 2026 match outcomes using multiple linear regression.

The assessment includes two predictive models:

# - Model 1: Predicting the goal difference between two opposing teams.
# - Model 2: Predicting the number of goals scored by an individual team.

Both models use eight explanatory variables to investigate how team performance and other characteristics relate to match outcomes.

## Group Members and Contributions

| Group Member      | Contributions                                                     |
| ----------------- | ----------------------------------------------------------------- |
| Roisin            | Model 1 Python coding, analysis, and individual report section    |
| Krupa Maria Salim | Model 2 Python coding, analysis, and individual report section    |
| Mariam            | Contributed datasets and preparation of the combined group report |

All three members participated in researching, identifying, and sharing explanatory variables and relevant datasets.

# Repository Contents

The repository contains materials contributed by all three group members.

# Krupa – Model 2

This folder contains:

- Raw and final datasets
- Model 2 Python notebooks
- Data preparation and regression analysis
- Model evaluation and visualisations
- Individual Model 2 report
- AI usage declaration

# Mariam – Datasets

Contains datasets collected and shared by Mariam for the group assignment.

# Roisin – Model 1

Contains a ZIP archive of Roisin's contributed files, including her Model 1 materials.

# Modelling Approach

Both models use multiple linear regression with explanatory variables selected to represent relevant team characteristics.

The analysis involves data preparation, exploratory data analysis, regression modelling, and evaluation of model performance.

# Model 2 Results

Model 2 uses 208 team-match observations and eight explanatory variables.

| Metric | Linear Regression | Baseline |
| ------ | ----------------: | -------: |
| MAE    |            1.0321 |   1.2461 |
| MSE    |            1.7807 |   2.2121 |
| RMSE   |            1.3344 |   1.4873 |
| R²     |            0.1779 |  -0.0213 |

These results indicate that Model 2 performed better than the baseline, although its predictive accuracy remained limited.

# Data Limitations

The assessment required explanatory variables to represent pre-match information. Some contributed historical variables require further verification to establish whether they fully satisfy this requirement.

# Running the Python Code

The Python notebooks are stored within the relevant members' files.

For Model 2:

1. Open `assessment3_model2.ipynb` from Krupa's folder.
2. Keep `Model2_Plain_Corrected_208_Rows.xlsx` in the same directory.
3. Open the notebook in Jupyter Notebook or Visual Studio Code.
4. Install the required Python libraries, including pandas, numpy, scikit-learn, matplotlib, seaborn, statsmodels, and openpyxl.
5. Run the cells sequentially to reproduce the analysis.

Refer to Roisin's contributed files for the Model 1 implementation.

# Documentation

The repository contains individual coding files, supporting datasets, analysis materials, and report sections prepared during the assignment.




Foundations of Data Science | Charles Darwin University | 2026
