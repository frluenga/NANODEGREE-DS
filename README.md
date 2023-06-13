# Exploring Factors Impacting Salaries: Insights from a Survey of Stack Overflow Users
This README.md file provides an overview of the analysis conducted on a massive survey of Stack Overflow users. The survey encompassed various topics, including knowledge, income, geographic information, labor details, and other factors that allowed for a detailed descriptive analysis of the surveyed population.

## Project Motivation
The objective of this analysis was to explore the impact of different variables on salaries within the software development and related fields. By addressing specific questions, the aim was to gain a better understanding of factors such as education, self-teaching, and remote work benefits, and how they influence income levels.

## Installation
Please consult the installation file, there you will find the libraries that will be used in Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Key Findings
The analysis yielded several noteworthy findings:

* Salary Differences: Individuals who engaged in coding as a hobby and contributed to open-source projects had a higher average salary compared to those who did not pursue these activities.

* Doctorate Impact: Having a doctorate degree was associated with a significantly higher average salary compared to other types of education, even surpassing the average salary of those with a Bachelor's degree.

* Years of Programming Experience: Salary distributions were directly proportional to the number of years spent programming. Those with more years of experience tended to earn higher incomes.

* Salary Disparity: Respondents with over 20 years of programming experience had considerably higher salaries compared to those who were just starting out.

* Self-Taught Advantage: Self-taught individuals had higher average salaries compared to those who did not pursue self-teaching.

* Remote Work Benefits: While there was only a marginal difference, respondents who valued remote work benefits were more likely to earn higher salaries.

Regression Model: An XGB regression model was trained to predict income based on the analyzed variables. The model achieved a 39% accuracy in capturing the variance of income.

# Results
The main findings of the code can be found at the post available https://medium.com/@frluenga/does-the-salary-determine-that-you-are-happiest-in-your-job-a8b2d2ce1982.

Licensing, Authors, Acknowledgements
Must give credit to Stack Overflow for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available https://www.kaggle.com/datasets/stackoverflow/so-survey-2017 . Otherwise, feel free to use the code here as you would like!
