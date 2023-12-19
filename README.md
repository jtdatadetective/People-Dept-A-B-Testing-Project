# People-Dept-A-B-Testing-Project
Portfolio project demonstrating an A/B testing project for the People Department of a fictitious company

This project was completed in a Jupyter Notebook using Python 3.  The purpose of this project is to demonstrate knowledge of A/B testing and python coding skills
and how that can be applied to solve an organizational problem.  

A/B tests are very commonly performed by data analysts to test for statistical significance between two means and whether a difference occurred by chance. 
For this project, I will be utilizing A/B testing to help the People Department of a fictitious company determine if their recruiting efforts are significantly different 
with application process 1 vs. application process 2.

Scenario: The company is having trouble recruiting for an hourly position with a tight labor market and competitive wages and they want to ensure that the current application 
process is not dissuading applicants due to its complexity. They have developed a new simplified application process and they want to test it to see if it helps to increase applications.

For this analysis, application process 1 is the existing online process being used and will be the control group. The new simplified online process - application process 2 - will be 
the treatment group. Applicants during the test period were randomly directed from the company's career page to either the control group application page or to the treatment group application 
page to complete the process. Converted (1) indicates that the user completed the application process, whereas (0) indicates that the user abandoned the process and did not submit an application.

In this project, the null hypothesis is that the rate of conversions for application process 1 is the same or better than that of application process 2. The alternative hypothesis is that 
the conversion rate is higher for the new application process - the treatment group. The goal of this analysis is to use statistics to reject/not reject the null hypothesis in order to assist the 
company in deciding which application process to use going forward.

Note: Data sourced from Kaggle https://www.kaggle.com/datasets/zhangluyuan/ab-testing. Data was modified to fit the needs of this analysis.
