# Proposal for Basketball Game Analytics Project

## Title

**Analyzing Performance Trends in NBA Basketball**
## Team

- Collin Kneiss (GitHub ID: cjkneiss ) - Point of Contact (POC)
- Ankit Waikar (GitHub ID: awaikar-syr)
- Odbileg Erdenebileg (GitHub ID: odko123)

# Introduction
Our project aims to analyze and visualize performance trends in NBA basketball using historical player and team statistics. This analysis will help uncover patterns that can predict future performance and inform strategic decisions in coaching and player development. The objective is to provide actionable insights that are easily interpretable by coaches, analysts, and fans alike.

Currently, the analysis of NBA team performance often relies on basic statistics. Our approach utilizes advanced statistical modeling combined with machine learning techniques to derive insights from a comprehensive dataset of NBA statistics, which has not been extensively explored in existing literature. If successful, our project will not only enhance decision-making processes within teams but also enrich the viewing experience for fans.

# Literature Review
Current practices in basketball analytics often depend on traditional metrics like points, assists, and rebounds. However, these methods are limited in their ability to account for contextual factors such as game location, opponent strength, and player fatigue. Recent studies have highlighted the use of advanced metrics like Player Efficiency Rating (PER) and Win Shares, but there remains a gap in applying machine learning techniques to predict team performance based on a broader range of features  .

Stakeholders for this project include:
- **Coaches:** Who need data-driven insights to enhance game strategies and player performance.
- **Sports Analysts:** Seeking comprehensive performance data for in-depth analysis.
- **Fans:** Interested in understanding player performance trends and team dynamics.
- **Teams/Organizations:** Looking to leverage data for informed recruitment and investment decisions.

# Data and Methods

## Data
We will utilize datasets from [Basketball Reference](https://www.basketball-reference.com/) and the NBA API. The primary dataset contains the following columns related to NBA team statistics:

| Column | Explanation |
|--------|-------------|
| Rk | Rank of the team in the league based on overall performance. |
| Team | The name of the basketball team. An asterisk (*) may indicate a playoff team. |
| G | Total number of games played by the team during the season. |
| MP | Minutes Played per game by the team as a whole. |
| FG | Field Goals made per game. |
| FGA | Field Goals Attempted per game. |
| FG% | Field Goal Percentage, calculated as FG divided by FGA. |
| 3P | 3-Point Field Goals made per game. |
| 3PA | 3-Point Field Goals Attempted per game. |
| 3P% | 3-Point Percentage, calculated as 3P divided by 3PA. |
| 2P | 2-Point Field Goals made per game. |
| 2PA | 2-Point Field Goals Attempted per game. |
| 2P% | 2-Point Percentage, calculated as 2P divided by 2PA. |
| eFG% | Effective Field Goal Percentage. |
| FT | Free Throws made per game. |
| FTA | Free Throws Attempted per game. |
| FT% | Free Throw Percentage. |
| ORB | Offensive Rebounds per game. |
| DRB | Defensive Rebounds per game. |
| TRB | Total Rebounds per game. |
| AST | Assists per game. |
| STL | Steals per game. |
| BLK | Blocks per game. |
| TOV | Turnovers per game. |
| PF | Personal Fouls per game. |
| PTS | Points per game scored by the team. |
| Year | Year of the season these statistics represent. |

The dataset consists of over 1150 rows and 25 columns, ensuring a comprehensive view of team performance across multiple seasons. The data has been verified for reliability through cross-referencing with official league statistics.

## Methods
Our modeling approach will involve preprocessing the data to handle missing values and normalize features. We will explore various statistical techniques and machine learning algorithms, including regression analysis and ensemble methods like Random Forest and Gradient Boosting, to predict team performance metrics. Model evaluation will be aligned with stakeholders' needs, focusing on metrics like R-squared values and Mean Squared Error (MSE).

# Project Plan
| Period       | Activity                                                       | Milestone                                               |
|--------------|---------------------------------------------------------------|--------------------------------------------------------|
| [10/9] - [10/23] | Stakeholder analysis, EDA, and initial modeling with regression techniques | Completed stakeholder analysis and data exploration.   |
| [10/23] - [11/20] | Data preprocessing and applying machine learning algorithms | Initial pass with cleaned data and model predictions. |
| [11/20] - [12/01] | Model evaluation and final report preparation | Completed evaluation and submitted final report.      |

# Risks
Potential risks include:
- **Data Quality Issues:** If the data is found to be unreliable, we will identify alternative datasets and re-evaluate our modeling approach.
- **Model Overfitting:** To mitigate this, we will implement cross-validation techniques to ensure our model generalizes well to unseen data.
- **Time Constraints:** If we fall behind schedule, we will prioritize key milestones to ensure project completion.

### References
1. "Predicting Outcomes of NBA Basketball Games" - Eric Scot Jones
- The author created a point spread model and logistic regression to predict game outcomes for an NBA season. Using moving averages and seasonal averages, the author was able to account for 94% of the variation in game outcomes. Using the models and regressions, the author was able to predict between 60-75% of the playoff teams in the three test seasons. The author stated that certain statistics to include accuracy would have been useful. We intend to add in numerous statistics that the author left out in order to create more substansive models that misses some of the variance the author saw.

- Jones, Eric Scot. Predicting Outcomes of NBA Basketball Games. Master's thesis, North Dakota State University of Agriculture and Applied Science, April 2016. https://library.ndsu.edu/ir/bitstream/handle/10365/28084/Predicting%20Outcomes%20of%20NBA%20Basketball%20Games.pdf?sequence=1

2. "Predicting Which Teams will Make the NBA Playoffs" - Ryan Elmore
- The author uses logistic regression to predict playoff probabilty throughout the season. As the season advanced, the author wanted changing probabilities which were influenced by the team's record and potential at that specific point. Using data from basketball reference, the author created models which predicted team outcomes based on their statistics and running averages to determine probabilities. The author mentions missing effects for players on the team as a potential addition that would be useful to make the model better. We plan on incorporating for superstar talent to determine the effects of having better talent (better players will make a difference down the stretch).

- Elmore, Ryan. "Predicting Which Teams Will Make the NBA Playoffs." Statistica Applicata - Italian Journal of Applied Statistics, vol. 30, no. 2, 2020, pp. 213-229, http://dx.doi.org/10.2139/ssrn.2764482

## Timeline
By [Oct 9]: Proposal

By [Oct 23]: Data Analysis (EDA)

By [Nov 6]: Classification / Regression

By [Nov 20]: Results Interpretation

By [Nov 27]: Reports & Slides

By [Dec 1]: Polish 
