# Medical-Appointment-No-Shows

## Project Background
This dataset includes around 110,000 registration records of Brazilian patients.
In this analysis, I'm going to look at a dataset showing the turnout rate for those over 100 thousand medical appointments and I focus on determining what factors influenced some patients to show up and others to not show up.

## Tools Used
* numpy
* pandas
* matplotlib
* datetime
* seaborn

## Analysis Steps
1. Wrangling
   > check the data,missing value, incorrect data type, duplicates
2. Exploratory Data Analysis
   > create new features, remove outliers
3. Explore correlation between other variables and no-show

## Conclusion
1. longer awaiting-days(with16averageawaitingdays) and age between10 to 30 are more likely to no-show.
2. We can’t get causality from this correlation analysis.More statistic analyses are needed.
