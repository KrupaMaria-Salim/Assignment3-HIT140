# Model 2.2: Predicting Goals Scored by a Team (FIFA World Cup 2026)

**Marium Akter Mim, S397784**
HIT140 Foundations of Data Science, Assessment 3 (revised scope), Charles Darwin University, 2026

This folder has my own complete version of Model 2.2. It predicts how many goals one team scores in a World Cup 2026 match, using 208 rows and 8 explanatory variables that are all known before the match.

## What is in this folder

| File | What it is |
|---|---|
| `marium_model22.ipynb` | My notebook: data checks, exploration, the improvement, model comparison, cross validation and charts. Already run, so all outputs are saved. |
| `marium_model22_data.csv` | The 208 row dataset used by the notebook. |
| `Marium_Model2.2_Report.docx` | My 2 page report on this model. |
| `charts/` | The charts made by the notebook. |

## My improvement

The original 8 variables only describe the team itself, so the model could not tell an easy match from a hard one. I replaced Team xG (which repeats Average Goals Scored and had invalid values for Panama) with the **opponent's FIFA ranking**, built from the same dataset.

| | Model A (group, original Model 2.2) | Model B (Marium, improved) |
|---|---|---|
| Test MAE | 1.218 | **1.124** |
| Cross validated R² | 0.103 | **0.180** |

## How to run

1. Keep `marium_model22.ipynb` and `marium_model22_data.csv` in the same folder.
2. Install: pandas, numpy, scikit-learn, statsmodels, matplotlib.
3. Open the notebook in Jupyter and choose **Run All**.

## Data credits

The 208 row dataset was put together by our group (Krupa compiled the combined file).

| Variable | Collected by |
|---|---|
| Average_Age, Average_Goals_Scored | Marium Akter Mim |
| Team_xG | Krupa Maria Salim |
| Transfers_2025, Coach_Salary_EUR, FIFA_Ranking_Apr2026, Forward_Goal_Rate, Squad_Goals | Róisín |
| Goals_Scored (match results) | Official World Cup 2026 fixture list |

Sources: FIFA World Cup 2026 squad lists (age), International Football Results dataset by Mart Jürisoo on GitHub (average goals scored), FootyStats (xG), Salary Leaks (coach salary), FIFA ranking April 2026.

