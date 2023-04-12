# Visualizing-Predicting-Suicide-Rates

The notebook aims to explore and analyze global suicide rates from 1985 to 2016, using data from the World Health Organization (WHO) and the United Nations Development Programme (UNDP).

## Requirements
To run the notebook, you will need to have R installed on your local machine. Additionally, you will need to install the following packages:
* ggplot2
* dplyr
* tidyr
* lmtest

## Dataset
The dataset used in the notebook is available on Kaggle and is licensed under the Open Database License. The dataset contains information on suicide rates, GDP, unemployment, education, and population by country, gender, age group, and year.
https://www.kaggle.com/code/lmorgan95/r-suicide-rates-in-depth-stats-insights/input

## Contents
* DV_Suicide.Rmd - the R Markdown file containing the analysis
* DV_Models.ipynb - the Jupyter Source File containing prediction
* DV_Visuals.ipynb - the Jupyter Source File containing visualization
* WorldMapSuicide.twb - the Tableau Worksheet containing world map highlighting suicide rates
* master.csv - the dataset used in the analysis

## Result
The best model predicting Suicide rates for upcoming year was Random Forest Classifier showing accuracy 98.73%
