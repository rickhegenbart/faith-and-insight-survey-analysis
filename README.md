# faith-and-insight-survey-analysis

Project Overview
This project analyzes survey data exploring the relationship between cognitive insight and religiosity. Cognitive insight was measured using the Beck Cognitive Insight Scale, while religiosity was measured using the Centrality of Religiosity Scale. The analysis also reviewed whether age and gender were associated with insight and religiosity scores.
The project was completed in R using statistical modeling and data visualization. Methods included linear regression, one-way ANOVA, multi-factor ANOVA, MANOVA, diagnostic plots, and score visualizations. Overall, the analyses did not show statistically significant relationships between religiosity, cognitive insight, age, or gender in this sample.
Research Question
The main research question was:
Is there a meaningful relationship between participants’ religiosity scores and cognitive insight scores?
The project also explored whether age and gender were associated with differences in religiosity or cognitive insight scores.
Dataset
The dataset contains survey responses from 45 participants. It includes participant-level scores for religiosity and cognitive insight, along with demographic variables such as age group and gender.
Cognitive insight measure: Beck Cognitive Insight Scale
Religiosity measure: Centrality of Religiosity Scale
Sample size: 45 participants
Key variables: participant number, total score, insight total, religiosity total, age group, and gender
If the original dataset contains participant information or cannot be publicly shared, the GitHub repository should include a short note explaining that the data is excluded for privacy reasons.
Tools and Libraries
R
R Markdown
tidyverse
ggplot2
ggfortify
ggpubr
knitr
plotly, sciplot, and lsr if used in the final notebook
Methods
Descriptive summary of the dataset
Bar chart of overall participant scores
Linear regression comparing religiosity totals and cognitive insight totals
Regression diagnostic plots
One-way ANOVA examining religiosity and insight scores
Multi-factor ANOVA examining religiosity, age, gender, and insight scores
MANOVA examining age and gender in relation to religiosity and insight scores
Visualizations comparing score patterns by age group and gender
Key Findings
The sample included 45 participants.
Linear regression did not show a statistically significant relationship between religiosity and cognitive insight.
The one-way ANOVA also did not show a statistically significant relationship between religiosity and insight scores.
Age and gender were not statistically significant predictors of insight scores in the multi-factor ANOVA.
The MANOVA did not show significant combined effects of age and gender on religiosity and insight scores.
Descriptive plots suggested possible score differences across age and gender groups, but these differences were not statistically significant.
The small sample size and limited demographic diversity may have reduced the ability to detect meaningful relationships.
Visualizations
The R Markdown file includes several visualizations and diagnostic plots:
Overall participant score bar chart
Regression diagnostic plots
ANOVA diagnostic plots
Scores by age group
Scores by gender
MANOVA-related visualizations by age and gender
Recommended Repository Structure
faith-and-insight-survey-analysis/
│
├── README.md
├── Faith_and_Insight_Analysis.Rmd
├── Faith_and_Insight_Analysis.html
├── data/
│   └── FaithandInsight.csv
├── figures/
│   ├── participant_scores.png
│   ├── regression_diagnostics.png
│   ├── age_group_scores.png
│   └── gender_scores.png
└── references/
    └── references.md
How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/faith-and-insight-survey-analysis.git
2. Open the project folder
cd faith-and-insight-survey-analysis
3. Open the R Markdown file
Open the following file in RStudio:
Faith_and_Insight_Analysis.Rmd
4. Install required packages
install.packages(c("tidyverse", "ggfortify", "ggpubr", "knitr"))
5. Load the dataset
If the dataset is included in the repository, the notebook should load it with code similar to:
FaithandInsight <- read.csv("data/FaithandInsight.csv")
Limitations
The sample size was small, with only 45 participants.
The sample may not have been demographically diverse enough to detect meaningful differences.
The analysis was correlational and cannot establish causation.
Some descriptive group differences appeared in visualizations but were not statistically significant.
The original notebook should clarify variable coding for age and gender.
Future versions should include cleaner data documentation and clearer interpretation of statistical tests.
Future Improvements
Collect a larger and more diverse sample.
Improve documentation for the survey variables and score calculations.
Add cleaned figures as exported image files in a figures folder.
Create a reproducible data-loading workflow.
Add a short data dictionary explaining each column.
Refine the statistical interpretation and avoid causal wording.
Export the R Markdown notebook as an HTML report for easier viewing on GitHub.
Suggested README Text for GitHub
The following text can be copied into a GitHub README.md file:
# Faith and Insight Survey Analysis


## Project Overview


This project analyzes survey data exploring the relationship between cognitive insight and religiosity. Cognitive insight was measured using the Beck Cognitive Insight Scale, while religiosity was measured using the Centrality of Religiosity Scale. The analysis also reviewed whether age and gender were associated with insight and religiosity scores.


The project was completed in R using regression analysis, ANOVA, MANOVA, and data visualization. The results did not show statistically significant relationships between religiosity, insight, age, or gender in this sample. The findings are limited by the small sample size and limited demographic diversity.


## Key Findings


- The sample included 45 participants.
- Linear regression did not show a statistically significant relationship between religiosity and cognitive insight.
- One-way ANOVA did not find a significant difference in insight scores based on religiosity scores.
- Age and gender were not statistically significant predictors of insight scores.
- MANOVA results did not show significant combined effects of age and gender on religiosity and insight scores.
- Descriptive patterns suggested some group differences, but these were not statistically significant.


## Limitations


The sample size was small, with only 45 participants, which limits statistical power. The participant pool may not have been demographically diverse enough to detect meaningful differences across age and gender groups. The analysis was correlational, meaning the results cannot establish causation. Future research would benefit from a larger and more diverse sample, clearer variable coding, and additional measures related to belief, reflection, and psychological insight.
References
Beck, A. T., Baruch, E., Balter, J. M., Steer, R. A., & Warman, D. M. (2004). A new instrument for measuring insight: The Beck Cognitive Insight Scale. Schizophrenia Research, 68(2–3), 319–329.
Huber, S., & Huber, O. W. (2012). The Centrality of Religiosity Scale. Religions, 3(3), 710–724.
