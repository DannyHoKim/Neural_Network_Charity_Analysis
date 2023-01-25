# Neural Network Charity Analysis

## Overview of the analysis

The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results

### Data Preprocessing

1. Target Variables: The target variable of this model is contained in the "IS_SUCCESSFUL" column. This column indicates whether or not the applicant was successful or not.

2. Feature Variables: The features of this model include: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.

3. Removed Variables: The EIN variable was removed from this data set. 

### Compiling, Training, and Evaluating the Model

1. I kept the same amount of neurons and hidden layers.

2. Yes, I was able to achieve the target model performance.

3. I did not drop the NAME column and instead processed that data into input variables. I also created more bins for the NAME variables. I also changed the activation from relu to sigmoid for the two hidden layers; however, that did not have an impact of accuracy, so I returned both to relu. 


# Summary

It seems that the greatest impact on the accuracy score was by keeping the NAME variable within the data set. It increased the accuracy score from 54% to 75%. 