# Zeta Disease Prediction

## INTRODUCTION

Mars Mission Control needs a good data-driven system for predicting Zeta Disease infection on the International Mars Colony.
Use the `zeta-disease_training-data` dataset to build a model that can predict who will be infected by Zeta Disease.
Train and apply a classification model to the `zeta-disease_prediction-data` dataset to predict who will be infected by Zeta Disease.

## DATASET

The dataset includes 9 columns with information on 800 people.
1.	age : in years
2.	weight : body weight in pounds (lbs)
3.	bmi : Body Mass Index (weight in kg/(height in m)2)
4.	blood_pressure : resting blood pressure (mm Hg)
5.	insulin_test : inuslin test value
6.	liver_stress_test : liver_stress_test value
7.	cardio_stress_test : cardio_stress_test value
8.	years_smoking : number of years of smoking
9.	zeta_disease :
              1 = yes;
              0 = no


## Results

- `analysis.ipynb` is the main notebook containing the code for training and testing the model. It is also available for viewing as a HTML under `html-exports`.
- The environment used to perform the analysis is provided as a conda environment file - `zeta-env.yml`.
- The data visulaizations are saved as HTML and are placed under `html-exports` folder.
- The final predictions are placed under `predictions` folder.
