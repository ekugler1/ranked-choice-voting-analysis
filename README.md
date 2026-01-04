# ranked-choice-voting-analysis

# Ranked Choice Voting Support Analysis

## Project Overview
This project analyzes survey data to understand public support for Ranked Choice Voting (RCV) in the United States. Although RCV offers several benefits—such as identifying candidates with the strongest overall support and reducing wasted votes—not all voters support its adoption.

The purpose of this analysis is to help a civic engagement organization allocate educational and outreach resources more effectively. Rather than expending effort on populations that already support RCV or are unlikely to change their views, this project focuses on identifying demographic patterns associated with lower levels of support.

## Research Question
How do race and gender influence an individual’s likelihood of supporting Ranked Choice Voting?

## Data & Methodology
- Survey data measuring support for Ranked Choice Voting
- Focused on two demographic variables: **race** and **gender**
- Exploratory data analysis to identify patterns in support
- Built a **Decision Tree classification model**
- Evaluated model performance using a **confusion matrix** and **precision metrics**
- Conducted hypothesis testing to assess statistical differences in support across demographic groups

Race and gender were selected due to existing research demonstrating disparities in political participation, trust in electoral systems, and policy support across demographic groups.

## Results
The machine learning analysis identified **race as the most influential predictor** of support for Ranked Choice Voting. The decision tree model placed race at the top split, indicating its strong predictive importance.

Hypothesis testing further revealed statistically significant differences in support:
- **Black respondents** demonstrated a higher likelihood of supporting RCV
- **Women** showed stronger support for RCV compared to men

Model evaluation using a confusion matrix and precision scores provided insight into the model’s ability to correctly classify support and non-support, supporting the reliability of these findings.

## Implications
These results suggest that outreach and educational efforts may be most effective when focused on demographic groups exhibiting lower levels of support, particularly **White** and **male** populations. Understanding demographic variation in support allows organizations to design more informed, targeted, and efficient engagement strategies while avoiding redundant outreach.

## Tools & Technologies
- Python
- NumPy
- datascience
- scikit-learn (Decision Tree classification, evaluation metrics)
- Matplotlib

## Notes
The dataset used in this project was provided for academic coursework and is not publicly shareable.
