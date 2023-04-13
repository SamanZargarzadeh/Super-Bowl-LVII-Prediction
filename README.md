# Super Bowl LVII Prediction
Developing and presenting a model for Super Bowl prediction by utilizing data cleaning and feature engineering techniques, as well as implementing various machine learning models to predict the final score. Our team was selected to showcase our analysis at a sports event hosted by the university.


## Introduction

The methodology for this project involves two main components: sport analysis and machine learning models. The sport analysis component includes an examination of historical matches between the Kansas City Chiefs and Philadelphia Eagles, a quarterbacks analysis, a look at the 2022 performance, and a review of previous Super Bowl scores. The machine learning models component includes three different models: the Split Model, which is a linear regression model based on the splitting of data into two groups; the Five-Year Model, which combines logistic and linear models based on the last five years of Super Bowls; and the Performance Model, which is a linear regression model based on ELO rating and team performance. The accuracy of each model is reported and discussed in the Results chapter.

## Sport Analysis

    1. Historical Matches between chiefs and Eagles

    2. Quarterbacks Analysis

    3. 2022 Performance 

    4. Previous Super Bowls Scores
    
<img width="1784" alt="image" src="https://user-images.githubusercontent.com/88157400/231658642-e0192baf-6e80-49e7-b7a8-aa75493e72d6.png">

    
## Machine Learning Models
### Split Model    
Linear regression model based on the splitting data

    > 1. Divided the dataset into two groups, Kansas City Chief and Philadelphia Eagles.
    > 2. Created Dummy Variables of Wins & Losses corresponding to Home and Away Matches.
    > 3. Using Linear Regression, we used the scores of both Model and Time Series Forecasting to predict the score of the Final Match.
    
    > Average Accuracy: 74%


### Five-Year Model
Logistic + Linear model based on the last 5 years of super bowls

    > 1. Collect Data from 2018-2022
    > 2. Calculated the Average performance for each team per year
    > 3. Model prediction based on overall stats vs. final result
    
    > Accuracy: 81%

### Performance Model
Linear regression model based on ELO rating and team performance

    > 1. Merged two datasets of 2022 Matches and their ELO ratings
    > 2. Added attributes of the team performance for three latest games
    > 3. Predicted the log(score) of each match based on the log rating and the last three-games performances
    
    > Accuracy : 41%
    
## Ensemble Model
<img width="775" alt="Screen Shot 2023-04-12 at 10 06 52 PM" src="https://user-images.githubusercontent.com/88157400/231659206-e702872d-f0fa-428b-b327-259d36eda159.png">

## Super Bowl Prediction
<img width="885" alt="Screen Shot 2023-04-12 at 10 07 26 PM" src="https://user-images.githubusercontent.com/88157400/231659584-a8ccb889-248f-4c4e-9d0e-140993db9c03.png">


Team Name: Jadoo | Magic 
Team Members: S. Zargarzadeh, S. Sidhwani, T. Ebrahimi, A. Arora

