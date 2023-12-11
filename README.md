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
* Numpy to manipulate data into arrays for further calculation
* Pandas to analyze and visualize data
* Scikit-learn to implement statistical modeling and machine learning
