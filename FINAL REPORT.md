# NBA Playoff Prediction Project

This repository contains all files for our group project on predicting NBA playoff potential. The project is structured into several checkpoints, each with specific tasks and deliverables, culminating in a final report.

## Repository Structure

- **checkpoints/**: Contains folders for each checkpoint and the final report.
  - **checkpoint1/**: Initial data exploration and preprocessing.
  - **checkpoint2/**: Feature engineering and initial modeling.
  - **checkpoint3/**: Model refinement and evaluation.
  - **final-report/**: Comprehensive report detailing the entire project, including findings, challenges, and future work.

- **final-report/FINAL REPORT.md**: The final report document summarizing the project.

## Checkpoints

### Checkpoint 1
- **Objective**: Initial data exploration and preprocessing.
- **Deliverables**: Data cleaning scripts, exploratory data analysis (EDA) notebooks.

### Checkpoint 2
- **Objective**: Feature engineering and initial modeling.
- **Deliverables**: Feature engineering scripts, initial model training and evaluation.

### Checkpoint 3
- **Objective**: Model refinement and evaluation.
- **Deliverables**: Refined models, evaluation metrics, and visualizations.

## Final Report
- **Objective**: Present the entire project, including findings, challenges, and future work.
- **Deliverables**: Comprehensive report in `FINAL REPORT.md`.

## Team Members
- **Ankit Waikar** (GitHub ID: awaikar-syr) - Team Lead / Point of Contact (POC)
- **Collin Kneiss** (GitHub ID: cjkneiss)
- **Odbileg Erdenebileg** (GitHub ID: odko123)

## Project Overview

Our goal is to predict which NBA teams will make the playoffs and identify the key performance metrics driving success. By analyzing over 40 years of historical data, we aim to create a predictive model that provides actionable insights to coaches, analysts, and team front offices. The model focuses on metrics like shooting efficiency, defensive rating, and turnover management—areas that teams can actively influence to improve performance.

### Key Components
- **Data Collection**: Sourced from Basketball Reference, covering team performance from 1980 to 2021.
- **Data Preprocessing**: Cleaning, scaling, and handling multicollinearity.
- **Modeling**: Logistic Regression, Random Forest, and XGBoost.
- **Evaluation**: Cross-validation, accuracy, F1-score, AUC-ROC, and confusion matrices.

### Results
- **Best Model**: Gradient Boosting with the highest ROC-AUC.
- **Key Predictors**: Strength of Schedule (SOS), Defensive Rating, and Shooting Efficiency.

### Future Work
- Incorporate real-time game data and player-level statistics.
- Explore advanced modeling techniques and feature engineering.
- Develop an interactive tool for stakeholders.

## References
1. Basketball Reference: [https://www.basketball-reference.com](https://www.basketball-reference.com)
2. Advanced Basketball Metrics Literature: Relevant studies on [PER](https://www.cryptbeam.com/2020/11/11/advanced-statistics-and-plus-minus-data/), [Win Shares](https://www.basketball-reference.com/about/ws.html), and [ML applications in sports analytics](https://www.tandfonline.com/doi/full/10.1080/24751839.2021.1977066#d1e1239).

---
