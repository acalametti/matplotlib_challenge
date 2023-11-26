# matplotlib_challenge

Contributor: Alex Calametti 


## Overview

This script performs analysis on mouse data and study results, with a focus on drug regimens and their effects on tumor volume. It covers data cleaning, summary statistics, visualization through bar and pie charts, identification of potential outliers, and the exploration of correlations between variables.

## Dependencies

You will need the following dependencies installed:

- `matplotlib` 
- `pandas`
- `scipy` 
- `numpy`

Files used: 

- Mouse_metadata.csv
- Study_results.csv
- pymaceuticals_starter.ipynb

## Part 1: Data Cleaning and Exploration

The first part of the script involves loading mouse metadata and study results, combining them into a single DataFrame, and addressing any duplicate data. The duplicate mouse with the ID "g989" was identified and removed from the dataset.

## Part 2: Summary Statistics

Summary statistics were generated for each drug regimen, including mean, median, variance, standard deviation, and standard error for the tumor volume.

EX:


![Screen Shot 2023-11-26 at 5 36 08 PM](https://github.com/acalametti/matplotlib_challenge/assets/136642574/9cabcfb6-3d4c-4c5f-a086-bebbfc68d649)


## Part 3: Bar and Pie Charts

Bar charts are created to visualize the total number of observed mouse timepoints for each drug regimen. Additionally, pie charts were created to illustrate the distribution of female versus male mice in the population.

EX:

![Screen Shot 2023-11-26 at 5 36 39 PM](https://github.com/acalametti/matplotlib_challenge/assets/136642574/2b3ce831-a638-44a8-a5a1-0dafbd0bf84b)


![Screen Shot 2023-11-26 at 5 36 47 PM](https://github.com/acalametti/matplotlib_challenge/assets/136642574/3860b4fa-6220-4aa3-b92e-f022150a54e3)


## Part 4: Quartiles, Outliers, and Boxplots

The script calculates the final tumor volume for mice treated with specific drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) and identifies potential outliers using boxplots.

EX: 

![Screen Shot 2023-11-26 at 5 36 56 PM](https://github.com/acalametti/matplotlib_challenge/assets/136642574/b7cadc0f-b86f-4415-b289-7b8dfeec0d2e)


## Part 5: Line and Scatter Plots

A line plot demonstrates the tumor volume over time for a single mouse treated with Capomulin. Additionally, a scatter plot explores the relationship between mouse weight and the average observed tumor volume for the entire Capomulin regimen.

EX:

![Screen Shot 2023-11-26 at 5 37 11 PM](https://github.com/acalametti/matplotlib_challenge/assets/136642574/0765d174-6287-41e9-8267-aa1e135bf5c0)


## Part 6: Correlation and Regression

The script calculates the correlation coefficient and performs linear regression analysis to explore the relationship between mouse weight and average observed tumor volume for the Capomulin regimen.


## Thanks

Big thanks to my tutor Geronimo Perez for helping me troubleshoot! 
