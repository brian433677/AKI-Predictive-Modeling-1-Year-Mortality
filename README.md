**AKI 2-Year Mortality Predictive Modeling**


This project aims to create a 2-year mortality predictive model for AKI(Acute Kidney Injury) patients using Neural Network, on a public database called MIMIC-III, which comprises of deidentified health-related data associated with over 40,000 patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012


The purpose of this project is to use existing patient's information to create a mortality predictive model for AKI (Acute Kidney Injury) patients, within a 2-year timeframe


The workflow of this project is as follow:

-Create a comprehensive demographics of patients based on MIMIC-iii, including age of death and discharge.

-Create tables to fit patient's laboratory results during each admission using PostgreSQL

-Add important measurements and indications that are highly relevant to patients' demographics through connection to PostgreSQL using psycopg2

-Train a model through neural network

-Extract top most important features then optimize accuracy through hyperparameter tuning and K feature selection

Results:

Neural Network givse me around 90% of accuracy, which is decent. Further input features addition could lead to improved accuracy





