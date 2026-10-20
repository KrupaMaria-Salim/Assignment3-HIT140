# Model 2.2 – Predicting Goals Scored Using Linear Regression

**Student:** Krupa Maria Salim  
**Student ID:** S398540  
**Unit:** HIT140 – Foundations of Data Science  
**Assessment:** Assessment 3  
**University:** Charles Darwin University  
**Semester:** 2, 2026

## Project Overview

This folder contains my individual contribution to Model 2.2 of our FIFA World Cup 2026 group assignment. The objective was to predict the number of goals scored by an individual team using multiple linear regression.

I was responsible for developing the Model 2 Python code, including data preparation, analysis, modelling, evaluation, and visualisations. I also prepared my own report section explaining the methodology and findings.

The Python coding for this model was completed as my individual responsibility, using datasets and variables collected through our group work.

## My Individual Contributions

My main contributions included:

- Researching and collecting variables and datasets for both Model 1 and Model 2.
- Sharing data, findings, and updates with the group through Microsoft Teams.
- Combining and preparing the Model 2 dataset.
- Developing the Model 2 Python code using Jupyter Notebook.
- Performing data cleaning, exploratory analysis, regression modelling, and model evaluation.
- Creating visualisations and interpreting the results.
- Preparing my original Model 2 report section and a revised two-page version.
- Preparing an individual contribution statement documenting my work.

## Folder Contents

The folder `ASSESSMENT3_HIT140/Krupa` contains the following files:

| File | Description |
|---|---|
| `Dataset/` | Supporting datasets and source files collected during the assignment |
| `AI Usage Declaration Form v2(2).docx` | Declaration explaining my use of AI tools |
| Individual Contribution Statement | Explanation of my responsibilities, work completed, and challenges |
| `Model 2_REPORT_KRUPA.docx` | Original Model 2 report section prepared for the group submission |
| Model 2_REPORT_KRUPA_2 pages | Revised two-page Model 2 report prepared following the lecturer's instructions |
| `Model2_Plain_Corrected_208_Rows.xlsx` | Final dataset used for Model 2 |
| `README.md` | Documentation of my individual work and supporting files |
| `assessment3.ipynb` | Earlier Python notebook containing development work |
| `assessment3_model2.ipynb` | Main Python notebook containing the Model 2 analysis |

## Model 2 Analysis

The dataset contains 208 team-match observations and eight explanatory variables.

The Python analysis includes:

1. Loading and inspecting the dataset.
2. Checking missing values and duplicate records.
3. Cleaning and preparing the data.
4. Performing correlation analysis and VIF checks.
5. Developing the multiple linear regression model.
6. Applying train-test splitting and cross-validation.
7. Evaluating the model against a baseline.
8. Testing transformations and generating visualisations.

## Model Performance

| Metric | Linear Regression | Baseline |
|---|---:|---:|
| MAE | 1.0321 | 1.2461 |
| MSE | 1.7807 | 2.2121 |
| RMSE | 1.3344 | 1.4873 |
| R² | 0.1779 | -0.0213 |

The regression model performed better than the baseline, although its predictive accuracy remained limited.

## Challenges and Limitations

One significant challenge was checking whether all explanatory variables met the lecturer's requirement for pre-match information.

Some contributed variables required further verification. Since information was collected from different sources, checking and attempting to correct these issues required additional time and effort. Some concerns remained unresolved before submission.

These limitations should be considered when interpreting the results.

## Group Contributions

All three members participated in researching, identifying, and sharing variables and datasets for both models.

- **Roisin:** Model 1 Python coding, analysis, and individual report section.
- **Krupa Maria Salim:** Model 2 Python coding, analysis, visualisations, and individual report section.
- **Mariam:** Variable research, dataset collection, and preparation of the final combined group report.

The datasets were developed through group contributions. The Python coding and analysis presented in this folder document my individual responsibility for Model 2.

## Original Submission and Revised Documentation

My Model 2 code, datasets, and original report section were included in the group submission on 15 October 2026.

Following the lecturer's instructions, I also prepared a revised two-page Model 2 report and an individual contribution statement.

The README documents my contribution and helps distinguish the original files from the revised report materials.

## Running the Python Code

1. Download `assessment3_model2.ipynb` and `Model2_Plain_Corrected_208_Rows.xlsx`.
2. Keep both files in the same folder.
3. Open the notebook using Jupyter Notebook.
4. Install the required Python libraries if necessary.
5. Run the cells sequentially.

## AI Usage

AI tools were used to assist with understanding programming concepts, troubleshooting, reviewing code, and preparing explanations. Details are provided in my AI Usage Declaration Form.

---

HIT140 Foundations of Data Science | Assessment 3 | Charles Darwin University | 2026
