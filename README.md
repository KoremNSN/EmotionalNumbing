# High-threshold-low-tolerance: a model for the emotionality paradox in PTSD

In this project, we tried to see if people diagnosed with PTSD show a steeper transition between emotional states.
We fitted a 5-parameter logistic regression to ratings of valenced images.

Notebook 1 extracts the data from Qualtrics.
Notebook 2 wasn't used, but it tried to align the "objective" ratings - our participants were in agreement with themselves but less with the NAPS rating.
Notebook 3 cleans the data and removes outliers
Notebook 4 fit the 5 PL regression and compare the 2 groups
Notebook 5 adds emotional numbing as a regressor that contributes to the slope and compares it to a model with age, and age with interaction terms.
