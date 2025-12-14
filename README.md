End-to-end clinical risk modeling workflow: cleaning, EDA, logistic regression, decision tree, ROC/AUC
# Heart Disease Risk Prediction (Cleveland Dataset)

Predicting heart-disease presence using routine clinical measurements from the UCI Cleveland Heart Disease dataset.
This project compares interpretable baseline models (logistic regression and a decision tree) and evaluates performance using accuracy and ROC/AUC.

> Note: This was completed as a group project for an applied analytics course (INFO 659). The goal was clarity, interpretability, and a clean end-to-end workflow.

## What’s in this project
- Data cleaning and basic feature handling
- Exploratory analysis and simple visualizations
- Modeling:
  - Logistic Regression (baseline, interpretable)
  - Decision Tree (rule-based, easy to explain)
- Evaluation:
  - Confusion matrix / accuracy
  - ROC curve and AUC

## Key results (high level)
Logistic regression slightly outperformed the decision tree on our evaluation:
- Logistic Regression: Accuracy ≈ 0.85, AUC ≈ 0.92
- Decision Tree: Accuracy ≈ 0.83, AUC ≈ 0.86

(Exact values and plots are included in the report.)

## Repository structure
- `analysis/FinalProject.Rmd` — full analysis workflow (source)
- `report/FinalProject.html` — rendered report (easy to view in-browser)
- `report/FinalProject.pdf` — PDF version of the report
- `slides/INFO 659 - Group Project.pptx` — presentation slides
- `data/processed.cleveland.data` — dataset file used in the analysis (if included)

## How to run (R / RStudio)
1. Open `analysis/FinalProject.Rmd` in RStudio
2. Install required packages (RStudio will prompt if missing)
3. Knit to HTML or PDF

If the dataset is not included in this repo, download the Cleveland Heart Disease dataset and place it in `data/` with the expected filename used in the Rmd.

## Team contributions
- Ameen Aghazadeh: dataset selection, problem framing, visualization support, and slide development; presented final project
- Charlie Hammer: primary R implementation (cleaning/modeling/evaluation) and submission packaging; presented final project
- Alex Vasu: interpretation support, slide polishing/story structure; presented final project

## Data source
UCI Machine Learning Repository — Cleveland Heart Disease dataset (commonly used benchmark).

## Disclaimer
This is an educational project and is not medical advice. Any model outputs should not be used for real clinical decision-making.
