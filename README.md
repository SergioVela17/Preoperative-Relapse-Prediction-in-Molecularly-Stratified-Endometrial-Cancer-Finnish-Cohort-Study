# Preoperative-Relapse-Prediction-in-Molecularly-Stratified-Endometrial-Cancer-Finnish-Cohort-Study

This repository contains the code used to develop all the analyses described in the manuscript "Explainable Machine Learning for Preoperative Relapse Prediction in Molecularly Stratified Endometrial Cancer: A Single-Center Finnish Cohort Study".

The code starts with data loading, ensuring that there are no features included with more than 30% missing values and demographics table creation.
Afterwards, recursive feature elimination (RFE) is performed with each of the different datasets, obtaining the optimal set of features used for algorithm training. 
