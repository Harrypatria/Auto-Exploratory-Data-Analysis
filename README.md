### Auto-Exploratory-Data-Analysis

The EDA (Exploratory Data Analysis) is one of the important parts of the Data Science lifecycle stage (CRISP-DM Methodology). Automated EDA or AutoEDA can be used to have the following benefits:

- Ability to speed up the EDA analysis process
- Ability to save time and effort
- Ability to get preliminary analysis by capturing statistical insights, identifying missing values, duplicates, correlation, variable interactions, etc.
- Some of the options in Python are as follows.

![Alt Text](https://miro.medium.com/v2/resize:fit:786/format:webp/1*BUZ4YzU0l3FQvDifQZxkhg.jpeg)

Pandas Profiling
DTale
LUX
DataPrep
SweetViz
AutoViz
PyCaret
Mljar etc.
You may please refer to the following videos in the "AutoEDA" Series:

Intro and AutoEDA using Pandas Profiling: https://www.youtube.com/watch?v=KcWV-qMOB-c
AutoEDA using DTale: https://www.youtube.com/watch?v=2yHQm7zq0EQ
AutoEDA using LUX: https://www.youtube.com/watch?v=BwIao3Ixgmg
AutoEDA using DataPrep: https://www.youtube.com/watch?v=_REZYbWUa8w
AutoEDA using SweetViz: https://www.youtube.com/watch?v=uVLZJ2IA7eE
Notebook reference:
DataPrep: https://www.kaggle.com/kamal007/autoeda-loanprediction-dataprep/

Interpretation Summary for features on DataPrep:

Key Features

Analyze distributions
Analyze correlations
Analyze missing values
Analyze the difference between data frames
Creating profile report
When to use

Dataset size is fairly very large (this seems to be 10X faster than Pandas Profiling tools due to its highly optimized Dask-based computing module)
Need some quick insights about an unknown dataset
Use this as a basis for your further EDA analysis on top of it

- Installing required libraries
We will start by installing the Dataprep library by using pip. The command given below will do that.

- Importing required libraries

In this step, we will import the required libraries for loading the dataset, and performing EDA operations.

- Loading Dataset
For this article, we will use the famous Adult dataset that is predefined in Dataprep.


- Creating EDA Report
Now we will create an EDA report which contains all the Visualizations, Correlations, Missing Plots, etc which helps in analyzing the dataset.


![Alt Text](https://miro.medium.com/v2/resize:fit:828/format:webp/1*4eQvXzzRf6orEpQLKg1dpw.png)

- Plot Correlations

This plot creates different types of correlation plots showing correlations between different data variables.

![Alt Text](https://miro.medium.com/v2/resize:fit:720/format:webp/1*aqFMEsqhzsV5IMs3ex8tCw.png)

- Plot Missing

This is the final plot that helps in creating the table and charts which show missing data.

![Alt Text](https://miro.medium.com/v2/resize:fit:640/format:webp/1*BAITQzMgaBxOfkhE76xOWA.png)
