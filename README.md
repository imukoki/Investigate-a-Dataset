<h1 align="center">Project  1: Investigate-a-Dataset</h1>
<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Nanodegree </a></h3>

**Table of contents**

- [Introduction](#Introduction)
- [Data Wrangling](#Data-Wrangling)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Installation](#Installation)
- [Requirements](#Requirements)
- [Author](#Author)

## Introduction
In this project the dataset that is being investigated is the [TMDb Movie Dataset](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv) which has over 10000 movies with release dates dating from 1960 to 2015.

The questions that are investigated in this project are:
1. Investigating the trend in popularity of movies as the time progresses from 1960 to 2015
2. Investigating the correlation of popularity, budget, vote count with the revenue

## Data-Wrangling
The dataset is loaded into the Jupyter Notebook and checks are done to see if the dataset does not contain any missing values, upon checking it is discovered that there are variables with missing values. It is decided that all the missing values should be dropped so that all the variables have the same number of data points. Columns that were initially thought to not be useful in the investigation were dropped. The release date was converted to datetime so that it can be used to plot a time series to show the trend of some of the variables as time progresses. The dataframe was sorted in asscending order using the release date as the key, this made it easier to plot time series graphs.

## Exploratory-Data-Analysis
Statistics were computed and visualizations were created with the goal of addressing the research questions in the Introduction section. In this case time series plots and scatter plots were created to answer the research questions.

## Installation 

```
git clone https://github.com/imukoki/Investigate-a-Dataset.git
cd Investigate-a-Dataset
Jupyter notebook 
```

## Requirements
* Pandas
* Numpy 
* Matplotlib

## Author

👤 **Innocent Mukoki**

- GitHub: [Innocent Mukoki](https://github.com/imukoki)
- LinkedIn: [Innocent Mukoki](https://www.linkedin.com/in/innocent-mukoki/)
