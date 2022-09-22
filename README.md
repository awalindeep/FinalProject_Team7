
# FinalProject_Team7
### Toronto Raptors Analysis
#### 2018-2019 NBA Champion

## Project Goal

The goal of this project is to analyze Raptors performance during their participation in the 2018 -2019 NBA Championship. The goal is to analyze their performance based on various parameters (i.e. ). We will also perform Machine Learning on this data. We hope to explore various ML models that predict the game outcome based on a variety of factors. We will use accuracy as the measure to determine which ML model would work best.

This analysis will also aid coaches, sponsors and players, in better understanding their teams performance based on variables outlined in the analysis.


## Questions we want to answer


## Group communication protocols

-   

## Getting started


## Exploratory Data


## Machine Learning

Using the Raptors 2018-2019 Championship season data set we hope to  explore different machine learning models. The models we hope to use include oversampling, undersampling and combination sampling algorithms. Additionally we hope to use Ensemble learners; in using these we hope to extract feature importance. Overall the algorithms we will use are:

- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

### Primary ML Goal:
We hope to evaluate the performance of each model and make recomendations based on which model is the most accurate at predicting game outcome.

### Basic Data Cleaning and Input/Output Selection

The columns present in the dataset that we will be using are featured in the figure below:

![columns in raptors_regulars.PNG](https://github.com/awalindeep/FinalProject_Team7/blob/Claudia-Martin/Resources/Images/columns%20in%20raptors_regulars.PNG)

From these columns we will exclude the TEAM, MATCHUP, and Score (+/-). The X features will be the remaining columns excluding that which will be our target. Our target coulmn will be y = "W/L", this represents the outcome of the match.

After the appropriate data cleaning (joining the regular season and playoff data, removing null and missing data, and dropping the appropriate columns) we will use the above describe X and y to split the data into training and testing data sets. Using these data sets the models listed above will be evaluated. 

## Database

## Project dashboard

## Conclusion


## Resources
[![click](https://github.com/awalindeep/FinalProject_Team7/blob/Awalin-buttar/Resources/click.png)](https://github.com/awalindeep/FinalProject_Team7/tree/AwalinGHMAIN/Resources)

## Presentation

[![click](https://github.com/awalindeep/FinalProject_Team7/blob/Awalin-buttar/Resources/click.png)](https://docs.google.com/presentation/d/1Zr4hH1fCiVoQane84CiFByj1gcuTspphzM_FtJ9em2I/edit#slide=id.p)
