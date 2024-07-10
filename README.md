# Race/BPL Prediction

**Author:** Michael Cao  
**Advisor:** Prof. Wenfei Xu, Cornell University  
**Status:** In Progress

## Overview
This repository contains the code and research findings for an ongoing project focused on predicting race and foreign/native-born status based on the 1940 US census data. Led by Michael Cao under the supervision of Prof. Wenfei Xu, this research is part of the broader efforts of the Redlining Lab at the Urban Data Research Lab, Cornell University. The project aims to uncover demographic patterns influenced by historical redlining practices to inform equitable urban development policies.

## Objective
The primary objective is to develop a robust predictive model using Bayesian Improved Surname First-Name Geocoding (BISFG) techniques. This model will estimate probabilities of race and nativity for loan card records, contributing to a deeper understanding of urban inequalities exacerbated by historical redlining.

## Methods
The methodology involves:
- Cleaning and preprocessing 1940 census data for model training.
- Implementing BISFG algorithm with enhancements to handle diverse demographic scenarios.
- Evaluating model accuracy through validation and backtesting using sample census data.

## Results
Key results include:
- 97.80% coverage of loan card records with predicted probabilities.
- Approximately 80.5% accuracy in race prediction across five categories, improving to 83.5% with two categories.
- Approximately 81% accuracy in predicting foreign/native-born status.

## Contributors
- **Advisor:** Prof. Wenfei Xu
- **PhD Student:** Kate Thomas

## Additional Information
For more details and related published research, visit the [Urban Data Research Lab website](https://www.urbandataresearchlab.org/). A paper based on this research is pending publication.
