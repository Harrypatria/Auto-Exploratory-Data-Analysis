### Auto-Exploratory-Data-Analysis

####Installing required libraries
We will start by installing the Dataprep library by using pip. The command given below will do that.

!pip install -U dataprep
Importing required libraries
In this step, we will import the required libraries for loading the dataset, and performing EDA operations.

from dataprep.datasets import load_dataset
from dataprep.eda import create_report
from dataprep.eda import plot, plot_correlation, plot_missing
Loading Dataset
For this article, we will use the famous Adult dataset that is predefined in Dataprep.

df = load_dataset("adult")
Creating EDA Report
Now we will create an EDA report which contains all the Visualizations, Correlations, Missing Plots, etc which helps in analyzing the dataset.

create_report(df).show_browser()

![Alt Text](https://miro.medium.com/v2/resize:fit:828/format:webp/1*4eQvXzzRf6orEpQLKg1dpw.png)
