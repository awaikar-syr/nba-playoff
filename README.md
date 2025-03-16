
# NBA Playoff Prediction Project

This repository contains all files for our group project on predicting NBA playoff potential. The project is structured into several checkpoints, each with specific tasks and deliverables, culminating in a final report.

## Team Members
- **Ankit Waikar** (GitHub ID: awaikar-syr) - Team Lead / Point of Contact (POC)
- **Collin Kneiss** (GitHub ID: cjkneiss)
- **Odbileg Erdenebileg** (GitHub ID: odko123)

## Project Overview

### Problem
The goal of this project is to predict which NBA teams will make the playoffs. This is a machine learning problem because it involves analyzing historical data and identifying patterns that can be used to make predictions about future events.

### Stakeholders
- **Major Stakeholders**: NBA coaches, analysts, and team front offices.
- **Minor Stakeholders**: Sports journalists, fans, and sports betting companies.

### The Gap
Currently, NBA teams rely on traditional statistical analysis and expert opinions to make decisions about playoff potential. However, these methods can be subjective and may not fully capture the complexities of team performance. By using machine learning, we can provide more accurate and data-driven insights.

### Data
We are using historical data from Basketball Reference, covering team performance from 1980 to 2021. This data includes metrics such as shooting efficiency, defensive rating, and turnover management, which are crucial for predicting playoff success.

### Approach
Our approach involves several steps:
1. **Data Preprocessing**: Cleaning, scaling, and handling multicollinearity.
2. **Modeling**: Using Logistic Regression, Random Forest, and XGBoost to build predictive models.
3. **Evaluation**: Cross-validation, accuracy, F1-score, AUC-ROC, and confusion matrices to evaluate model performance.

### Results
The final outcomes of our work include:
- **Best Model**: Gradient Boosting with the highest ROC-AUC.
- **Key Predictors**: Strength of Schedule (SOS), Defensive Rating, and Shooting Efficiency.
- **Metrics**: The model achieved an F1-score of 0.85 and an AUC-ROC of 0.92. These metrics were generated using 10-fold cross-validation.
- **Visualizations**: Confusion matrices and feature importance plots are included in the final report.

### Discussion
We achieved our goal of predicting NBA playoff potential with a high degree of accuracy. Our model addresses the needs of our stakeholders by providing actionable insights into key performance metrics. However, there is still work to be done to fully address all stakeholder needs, such as incorporating real-time game data and player-level statistics.

### Limitations
Our work is limited by the quality and scope of the historical data used. We were unable to incorporate real-time data and player-level statistics due to resource constraints. Additionally, our model may not fully capture the complexities of team dynamics and other external factors.

### Future Work
Future steps include:
- Incorporating real-time game data and player-level statistics.
- Exploring advanced modeling techniques and feature engineering.
- Developing an interactive tool for stakeholders to use the model's predictions.

## Repository Structure

- **checkpoints/**: Contains folders for each checkpoint and the final report.
  - **checkpoint1/**: Initial data exploration and preprocessing.
  - **checkpoint2/**: Feature engineering and initial modeling.
  - **checkpoint3/**: Model refinement and evaluation.
  - **final-report/**: Comprehensive report detailing the entire project, including findings, challenges, and future work.

- **final-report/FINAL REPORT.md**: The final report document summarizing the project.

## References
1. Basketball Reference: [https://www.basketball-reference.com](https://www.basketball-reference.com)
2. Advanced Basketball Metrics Literature: Relevant studies on [PER](https://www.cryptbeam.com/2020/11/11/advanced-statistics-and-plus-minus-data/), [Win Shares](https://www.basketball-reference.com/about/ws.html), and [ML applications in sports analytics](https://www.tandfonline.com/doi/full/10.1080/24751839.2021.1977066#d1e1239).

---

This README provides an overview of the project structure and contents, guiding first-time viewers through the repository.