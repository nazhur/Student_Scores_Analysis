# Student Score Analysis Project

## Overview

This project aims to analyze student performance data across various factors such as demographic information, parental education, study habits, and engagement in extracurricular activities. The analysis provides insights into the factors influencing students' academic performance in Math, Reading, and Writing.

## Dataset Description

The CSV data file used in this analysis was downloaded from [Kaggle](https://www.kaggle.com)

The dataset used in this analysis contains information on students' scores in Math, Reading, and Writing, along with demographic details such as gender, parental education level, and number of siblings. Additionally, it includes data on students' study habits, engagement in sports, and test preparation.

## Analysis Summary

The analysis reveals several key findings:

1. **Effect of Being the First Child**:
   - Being the first child does not significantly impact academic performance compared to having multiple siblings.
   - Female students tend to have slightly higher scores across different family sizes.
   - Scores tend to decrease as the number of siblings increases.

2. **Impact of Parental Education and Weekly Study Habits**:
   - Students with parents holding higher degrees (bachelor's or master's) perform better in Math, Reading, and Writing.
   - Regular study habits (5-10 hours per week) correlate with higher scores, while irregular or no study habits show lower scores.

3. **Engagement in Sports and Test Preparation**:
   - Students who engage in sports regularly or sometimes tend to have higher scores.
   - Completing test preparation regularly is associated with higher academic achievement.

## Conclusion

The analysis underscores the importance of parental education, study habits, and engagement in extracurricular activities in promoting students' academic success. It provides valuable insights for educators, policymakers, and parents to develop strategies and interventions aimed at enhancing students' academic performance and overall well-being.

## Dependencies

- Python
- Pandas
- Matplotlib
- Seaborn

## Usage

To replicate the analysis, clone this repository and run the provided Jupyter Notebook or Python script using the required dependencies.

```bash
git clone https://github.com/your_username/student-score-analysis.git
cd student-score-analysis
jupyter notebook student_score_analysis.ipynb
