# Data-Scientist-Blog-Post
## Stack Overflow Data-2018 survey
## Table of contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installations <a name="installation"></a>
- This code runs with Python version 3.* and requires some libraries, to install theses libraries you will need to execute: </br>
  ` pip install -r requirements.txt `
- Numpy, Pandas, Matplotlib and Seaborn
- You will need to download Stackoverflow’s 2017 and 2018 Annual Developer Survey and put in specific folders. You can find the data to download [here](https://insights.stackoverflow.com/survey). </br>

## Project Motivation <a name="motivation"></a>
Every year, Stack Overflow conducts a massive survey of people on the site, covering all sorts of information like programming languages, salary, code style, and various other information. This year, they amassed more than 64,000 responses fielded from 213 countries.
For this project, I was interestested in using Stack Overflow data from 2017 to better understand:
- Which Machine learning framework most used by Data scientists? </br>
- How many years of coding experience need to become a Data scientist? </br>
- What is the correlation between framework Vs years of experience with the median salary? </br>

## File Description <a name="files"></a>
- **main.ipynb**: Notebook containing data analysis
- **survey_results_public.csv.gz** :Stackoverflow's 2018 Annual Developer Survey data. </br>
- **survey_results_schema.csv** :the questions that correspond to each column name. </br>

## Result <a name="results"></a>
- The logistic regression fits the data better than the decision tree model, considering both training and test data errors. From the coefficients of the logistic regression model, can predict which parameters will value to lead to work from home.
- My blog post https://medium.com/@puchalapalli.gowthami/stack-overflow-data-2018-survey-144502c96cc6

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Stackoverflow for the data. You can find the Licensing for the data and other descriptive information at the Stackoverflow link available [here](https://insights.stackoverflow.com/survey).
