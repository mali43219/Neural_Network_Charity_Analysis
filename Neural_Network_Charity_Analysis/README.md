# Neural_Network_Charity_Analysis

## Overview
    
The Purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing

1. Target: IS_SUCCESSFUL column
2. Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT columns
3. Neither Target or Feature: EIN and NAME columns

### Compliling and Training

1. I used 2 hidden layers and used relu functions for the first and sigmoid for the 2 other hidden layers.
2. no, the model had a 72% accuracy.
3.  I added an extra layer, to make it total 3 hidden layers and used relu function for the first and sigmoid for the 2 other hidden layers. This increased the accuracy to 73%, but not enough to make it 75%.



