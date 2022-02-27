# Predictive power of the big five personality traits

## Datasets
- Facial recognition technology can expose political orientation from naturalistic facial images, Michal Kosinski https://www.nature.com/articles/s41598-020-79310-1.pdf <br>
Dataset contains personality scores volunteered by 108,018 U.S. Facebook users recruited through an online personality questionnaire between 2007 and 2012. Participants were rewarded by the feedback on their scores and provided informed consent for their data to be recorded and used in research. Participants’ personality was measured using the 100-item International Personality Item Pool (IPIP) fvefactor model of personality questionnaire28, with a fve-point Likert-style response scale ranging from “strongly disagree” to “strongly agree.” Te scales’ Cronbach’s α reliability equaled 0.84, 0.92, 0.93, 0.88, and 0.93 for openness, conscientiousness, extraversion, agreeableness, and neuroticism, respectively

- Kaggle dataset of questionarrie answers https://www.kaggle.com/tunguz/big-five-personality-test <br>
This dataset contains 1,015,342 questionnaire answers collected online by Open Psychometrics (https://openpsychometrics.org/tests/IPIP-BFFM/).

## Methods
Logistic Regression, XGBoost and k-nearest neighbors are used to predict subjects' political orientation, gender and age. While predicting political orientation, logistic regression gave similar result to the one in the paper.

## Quick insights
- Subjects with high openness tend to be liberals.
- Big five personality traits predicts political orientation correctly 66% of the time.
- Most discriminating trait for gender is neuroticism, males have higher values of it.
- AUC score is 63% when predicting gender.
- Consciousness correlates .18 with age, and older subjects tend to be conservatives.
- RMSE score is 9 when predicting age. <br>
\* First two modeling notes here are for logistic regression, ridge regression has been used for the last.
