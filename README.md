# Udacity Data Science Nanodegree Project 1: Write a Data Science Blog Post

## Analysis of OECD Meat Consumption Data Analysis 1990-2019

## Description
Contains a jupyter notebook that answers the following questions:
- Which country had the highest mean meat consumption in tons? Which country had the highest mean meat consumption per capita?
- In what year was the most beef per capita consumed worldwide? What is the median worldwide beef consumption per capita? In what year was beef consumption closest to the worldwide median?
- Based on our data, what is the average Brazilians preferred meat?
- What type of meat has seen the greatest rise in consumption? Which has seen the lowest?
- How well can we predict the beef consumption by kg per capita?

## Summary of Results
- China consumed the most meat in tons while the United States consumed the most meat per capita.
- The most beef per capita worldwide was consumed in 2007. The median yearly beef consumption per capita worldwide was 6.682 kg/capita.  World beef consumption per capita approximated the median in 2002 and 2004.
- The average Brazilian's preferred meat between 1990 and 2019 was poultry.
- Poultry has seen the greatest rise in consumption and beef has seen a slight decline in consumption worldwide.
- The model used predicted beef consumption with an R2 of 0.66728 against the training data and an R2 of 0.65868 against the test data. Not bad!

## Data
The data was sourced from the Organization for Economic Co-operation and Development (OECD) website:
https://data.oecd.org/agroutput/meat-consumption.htm

## Motivation
This repository was created to satisfy the Udacity Data Science Nanodegree Project 1 requirement.

## Files
- Udacity_Project_1.ipynb : a Jupyter Notebook containing the analysis
- .ipynb_checkpoints/ : a directory containing the jupyter notebook saves
- meat_consumption.csv : data

## Packages and softwares used
- Python 3.8.3
- Python Packages (i.e. numpy, pandas, seaborn, matplotlib, sklearn.linear_model, sklearn.model_selection, and sklearn.metrics)
- Jupyter notebook

## Acknowledgements
-  Organization for Economic Co-operation and Development (OECD) website for dataset:
https://data.oecd.org/agroutput/meat-consumption.htm
