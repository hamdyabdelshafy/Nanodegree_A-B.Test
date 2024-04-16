# Udacity Data Analysis Advanced - Nanodegree Program
## Project 2: Analyze A/B Test Results
### By: Hamdy Abdel-Shafy
### May 2021

## Introduction
A/B tests are very commonly performed by data analysts and data scientists. For this project, I have been working to understand the results of an A/B test run by an e-commerce website. The goal is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Part I - Probability
To get started, we import necessary libraries and explore the dataset to answer some questions.

## Part II - A/B Test
We consider making the decision just based on all the data provided. We assume that the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. We perform hypothesis testing and calculate p-values.

## Part III - Regression
In this final part, we use logistic regression to see if there is a significant difference in conversion based on which page a customer receives. We also explore the impact of country on conversion rate using dummy variables.

### Conclusion
Under the current situations, we do not have sufficient evidence to conclude that the new_page would increase the conversion rate compared to the old_page. As well as, the conversion rate is not significantly affected by country (US, CA, and UK).
