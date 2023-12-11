# Employment-Treads-and-Salary-Analysis
Exploring employment and salary trends of the dataset, while examining years of experience, education levels, and job titles.

## Introduction

This project aims to reveal meaningful insights into employment trends and salary dynamics by analyzing the dataset. The focus is on exploring how age, gender, education, and job title all affect salary. Aiming to find trends and potential disparities in compensation within the workforce.

The project utilizes the data science tools NumPy and Pandas for data manipulation. Along with Scikit-learn, it helps to provide predictive modeling, enabling us to form predictions from the dataset.

### Key Questions

1. Are there significant gender-based variations in compensation?
2. Is there a relationship between the years of work experience and salary, and what are the highest-paying job titles?
3. What is the expected impact of different levels of education on future salary trends?

By addressing these questions, the project aims to contribute insight into the dynamics of employment and compensation, allowing a deeper understanding of the factors that may influence salary.

## Selection of Data

The dataset used for this project can be found on [Kaggle](https://www.kaggle.com/datasets). Kaggle is a platform for data scientists to help explore and analyze data from a reliable source. The creator of this dataset is Sinhasatwik and can be accessed here [Salary_Base_Data](https://www.kaggle.com/datasets/sinhasatwik/salary-base-data). 

The data has over 6,600 samples with 6 features including Age, Gender, Education Level, Job Title, Years of Experience, and Salary. To find trends and disparities between these factors and the salary of the employee. 

Preview of Data:
![Data](https://github.com/patela23ATWIT/Employment-Treads-and-Salary-Analysis/assets/90491468/c15a60a1-1a8d-4c48-82e7-2ef81d6b5b36)

The cleaning that had to be done to the "Salary_Data.csv" consisted of the removal of all empty rows. Along with the combining of "Master's" and "Master's Degree" in the dataset. Another thing that had to change was the years of experience for individuals who had 1.5 years converted to 1 and 0.5 years converted to 0. Otherwise, the dataset has not been changed or altered in any way. 

## Methods

Tools:
* Pandas to read, analyze, and visualize data.
* Matplotlib to use visualization to get a better understanding and further analyze the data.
* Scikit-learn to implement statistical modeling and machine learning.
* Jupyter Notebook software to run code through the notebook.

  ### Tools used within SciKit and Matplotlib:
  * Data Splitting: Using the sklearn.model_selection, split the data into a training and testing set. After using the prediction method on the test.
  * Linear Regression: Using the sklearn.linear_model, use the fit method to help draw a trendline between data points.
  * Visualization: Using matplotlib.pyplot, create graphs and plots in many different variations.

 ## Results
 
Throughout this analysis, many conclusions were drawn about a person's salary depending on the key factors of the dataset. First, let's take a look at salary discrepancies based on gender. In this dataset, it was found that the average male salary is $121,395.70 while the average female salary is $107,889.00. That's a difference between $13,506.70 in pay yearly between males and females on average. But to take a closer look at the differences in salary between gender groups, the focus is shifted to the top 50 males and females. The average salary of the top 50 males was $223,400.00 and $206,900.00 for the females but the difference is only greater now being at $16,500.00. Thus as we can see there is a significant gap between the salaries of males and females on average being over $10,000.00 a year. Although these results may be able to be explained within the dataset, after doing some more research it was found that there were roughly 300 more males with a Ph.D. and around 600 with a bachelor's than there are females within the dataset. So that could be a point where the dataset may have some bias within the random sample. It is also notable that there are 658 more males than females within this dataset. 
