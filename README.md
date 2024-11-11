Gender Gaps in Math Scores Analysis using PISA Data
This project replicates key analyses from Nollenberger et al. (2016) to examine gender disparities in math scores across various cultural contexts. Using the PISA dataset for second-generation immigrant students, the analysis explores the impact of gender equality on math scores, while controlling for several confounding factors.

Project Overview
Objective
The objective of this project is to understand how cultural beliefs, specifically gender equality, influence gender gaps in math scores. We focus on second-generation immigrants, who, despite sharing host-country institutions, are culturally influenced by their parents' country of ancestry.

Key Research Questions
What factors explain the observed lower average math scores of females relative to males?
Are females inherently less math-oriented than males, or are cultural factors a significant influence?
Approach
Replicate the math gender gap by ancestry country as a function of the Gender Gap Index (GGI).
Estimate and compare several regression specifications to observe the effect of gender, age, education, and cultural indicators on math scores.
Project Structure
data/: Contains the dataset Final_sample.csv, which includes the PISA test scores and associated demographic variables.
notebooks/: Jupyter notebooks used to perform the analysis and generate visualizations.
src/: Main Python scripts for data processing, regression analysis, and visualizations.
README.md: Overview and guidelines for this project.
Dependencies
This project requires Python 3.8+ and the following Python libraries:

pandas
numpy
matplotlib
seaborn
statsmodels
stargazer
