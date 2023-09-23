# Vehicle Booking Market Analysis

## Overview
This repository contains the code and data for the analysis of the Indian vehicle booking market. The goal of this project is to segment the market and develop a feasible strategy for entering the market by targeting profitable segments.

## Data Sources
We collected two datasets from data.gov.in:

1. **City Information Dataset:** This dataset includes details about various cities in India, such as population, literacy rates, and more.

2. **Road Network Dataset:** This dataset provides information about the road network in Indian cities, including road lengths and densities.

## Data Preprocessing
- We performed data preprocessing tasks such as removing irrelevant cities and states, correcting state names, and combining datasets.
- We used one-hot encoding to handle non-numerical data.
- We applied custom scaling to certain features to ensure meaningful weightage in the analysis.

## Regression Modeling
- We treated the problem as a regression task to predict the `state_weight` for different cities.
- We experimented with various regression algorithms, with the GradientBoostingRegressor producing the best results.
- The model achieved a low Mean Squared Error (MSE), indicating its accuracy in predicting `state_weight`.

## Repository Contents
- **Code:** Contains the Python code used for data preprocessing, regression modeling, and analysis.
- **Data:** Includes the raw datasets used for analysis.
- **Final Dataset:** Contains the cleaned and combined dataset for analysis.
- **README.md:** This file, providing an overview of the project.

## Usage
- Clone the repository to your local machine.
- Open and run the Jupyter Notebook or Python script to reproduce the analysis.
- Modify the code and experiment with different models or strategies.

## Contact
For questions or feedback, please contact [me](mailto:21it3004@rgipt.ac.in).

