# Credit_Risk_Analysis

## Overview
The purpose of this project was to use different types of machine learning algorithms to predit whether a loan would be approved or not. 

## Results
I found noticeable variation between the different types of machine learning. Below I have included a breakdown of my findings

### The Good
![ensemble](https://user-images.githubusercontent.com/83841580/137664759-49ef1726-5f9e-4966-9ce4-7dc1199cd824.jpg)
Ensemble was the clear winner in terms of accuracy with over 94%.
![balanced_random_forest_classifier](https://user-images.githubusercontent.com/83841580/137664768-caa0bc4e-c2b1-4654-8c47-077a4ad46bd9.jpg)  
The balanced random forest classifier was a close second with over 90% accuracy. Both options had identical precision and recall scores.

### The Bad
Smote oversampling, undersampling, and combination all produced the same underwhelming results with 64% accuracy. All 3 of these options had identical precision and recall scores. Both of those scores are lower than the first two options.
![smote_oversampling](https://user-images.githubusercontent.com/83841580/137664739-471aa147-2c53-4fb9-938e-01f04922655b.jpg)
![undersampling](https://user-images.githubusercontent.com/83841580/137664741-ee812376-ec59-441e-b3a7-b6d28db39f9b.jpg)
![combination](https://user-images.githubusercontent.com/83841580/137664770-4159500c-0ddb-4313-a11e-e96a57c19123.jpg)


### The Ugly
In dead last is naive random over sampling with only 57% accuracy. This option did score the same on precision and recall as the previous 3.
![naive_random_oversampling](https://user-images.githubusercontent.com/83841580/137664751-48755335-07ae-477e-b137-e3bccf062ccc.jpg)

## Summary
The obvious reccommendation would have to go to ensemble. It had the highest scores across the board and was extremely accurate. On the opposite end of the spectrum I would stay away from naive random oversampling as it was terribly inaccurate. 

