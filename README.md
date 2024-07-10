# Demographic-Inference Algorithm

**Author:** Michael Cao  
**Advisor:** Dr. Wenfei Xu, Cornell University 

## Overview
This repository contains the code and research findings for an ongoing project focused on predicting race and foreign/native-born status based on the 1940 US census data. Supervised by Dr. Wenfei Xu, this research is part of the broader efforts of the Redlining Lab at the Urban Data Research Lab, Cornell University. The project aims to uncover demographic patterns influenced by historical redlining practices to inform equitable urban development policies.
- **PPL_HHD.Rmd:** Cleans and preprocesses partitioned people and household data from the 1940 census to produce standardized datasets for model training.
- **Race Prediction.Rmd:** Implements the Bayesian Improved Surname First-Name Geocoding (BISFG) algorithm with relaxation logics for predicting race probabilities of loan card records.
- **BPL Prediction.Rmd:** Similar to Race Prediction.Rmd but focuses on predicting native/foreign-born status using historical census and demographic data.
- **Table Requests.Rmd:** Generates requested tables by integrating census data and loan card predictions to provide detailed demographic insights.

## Objective
The primary objective is to develop a robust predictive model using Bayesian Improved Surname First-Name Geocoding (BISFG) techniques. This model will estimate probabilities of race and nativity for loan card records, contributing to a deeper understanding of urban inequalities exacerbated by historical redlining.

## Methods
The methodology involves several key steps:

### 1. Data Cleaning and Preprocessing
- Cleaning and harmonizing the 1940 census data to ensure consistency and accuracy.
- Preprocessing steps include standardizing formats, handling missing values, and integrating supplementary demographic data.

### 2. Bayesian Improved Surname First-Name Geocoding (BISFG) Algorithm with Relaxation Logics
#### Algorithm Overview
The BISFG algorithm is tailored for demographic inference, integrating multiple relaxation logics to enhance prediction accuracy and efficiency:
- **Step 1:** Initial prediction based on surname and first-name using Bayesian inference techniques.
- **Step 2:** Iterative refinement based on geographical information (state-level) to adjust predictions.
- **Step 3:** Conditional logic to handle cases where predictions are uncertain or ambiguous, improving robustness across diverse demographic scenarios.
- **Step 4:** Introduction of relaxation logics that allow the algorithm to continue predicting even when standard conditions are not met, thereby increasing coverage rates.
- **Step 5:** Optimization of computational efficiency through streamlined processes and parallel computing techniques, ensuring scalability and speed without compromising accuracy.
  
#### Enhancements and Adaptations
- Integration of historical census data and demographic surveys to calibrate model parameters.
- Application of machine learning techniques to iteratively optimize surname-first-name matching and geocoding precision.
- Incorporation of probabilistic thresholds to manage uncertainty and increase prediction confidence.

### 3. Model Evaluation and Validation
- Evaluation of model performance through cross-validation techniques.
- Backtesting against historical census data to validate predictions across different geographic regions and demographic groups.
- Metrics include accuracy rates, precision-recall curves, and demographic parity assessments.

## Results
Key results from the project include:
- Achieving 97.80% coverage of loan card records with predicted probabilities.
- Attaining approximately 80.5% accuracy in race prediction across five categories, improving to 83.5% accuracy with two categories.
- Predicting foreign/native-born status with approximately 81% accuracy.

## Additional Information
For more details and related published research, please visit the [Urban Data Research Lab](https://www.urbandataresearchlab.org/). 
A paper based on the research findings is pending publication. Stay tuned for updates!
