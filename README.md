![Banner Photo](https://github.com/Aspiring-DataGod9000/West-Nile-Virus-Kaggle-Challenge/blob/main/west-nile-banner-photo.jpg)

A data-driven approach against West Nile Virus in Chicago


This project aims to develop the a machine learning model that can accurately predict the presence of West Nile Virus (WNV) in various locations in Chicago. 
We used a dataset available on [Kaggle](https://www.kaggle.com/competitions/predict-west-nile-virus/data). 

We tested several models including Random Forest Classifier, Adaptive (ADA) Boost Classifier, Gradient Boost Classifier and Stacking Classifier.

## Problem Statement

We are a team of data scientists at the Disease And Treatment Agency, division of Societal Cures In Epidemiology and New Creative Engineering. 

Due to the recent epidemic of West Nile Virus in the Windy City, the Department of Public Health set up a mosquito surveillance and control system. We are tasked to build a model that predicts the detection of the virus in various parts of the city and to derive an effective plan to deploy pesticides throughout the city.

We evaluated the models based on the **AUC ROC scores** (the higher, the better) against the test set and truly unseen data on Kaggle




## Data Dictionary

The Kaggle datasets provided are as follows:

|Dataset|Period Coverage|
|---|---|
|spray set|Contains data from 2011 and 2013|
|weather set|Contains data from 2007-2014 (8 years)|
|train set|Contains data from 2007 - 2013 (2 years interval)|
|test set|Contains data from 2008 - 2014 (2 years interval)|




## Structure

This project is organised into two notebooks: 

- Notebook 1: Data Cleaning & Exploratory Data Analysis 
- Notebook 2: Modelling & Model Evaluation

## Summary of Analysis

The ADABoost Classifier Model was the best performing model. 

The comparison of model scores are as follows: 

| Method | Train Score | Test Score |Kaggle Score|Evaluation|
| :-: | :-: | :-: | :-:|:-:|
| Random Forest Classifier (Baseline) | 99.99% | 93.82% | 67.85% |3rd|
| Adaptive (ADA) Boost Classifier | 98.82%  | 93.6%  | 72.72%  |1st|
| Gradient Boost Classifier | 92.57%  | 92.715%  | 60.91% | 4th |
| Stacking Classifier | 98.6% | 97.85%  | 71.33% | 2nd |





   

## Conclusions & Recommendations

We will achieve substantial costs savings if we target the spraying of adulticides on targeted areas based on the proximity to weather station 1. 

**Recommendations**

* Collaborate with meteorologists and researchers to further investigate the impact of weather and seasons on occurrence of WNV
* Improve data collection on pesticide sprays conducted in the city to accurately track the effectiveness of sprays in curbing the spread of WNV
* Engage with research scientists to further investigate the virus-carrying mosquito species (Culex Pipiens & Culex Restuans) to find other methods to effectively inhibit their growth and spread
