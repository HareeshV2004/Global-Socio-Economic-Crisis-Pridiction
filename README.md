Crisis Prediction and Analysis

This repository contains two Jupyter notebooks for analyzing economic indicators and predicting potential crises across countries using statistical methods. The project focuses on processing global economic data to identify risks related to inflation, food insecurity, and energy price shocks.

Project Overview





Objective: Analyze economic indicators (e.g., inflation rates, food prices, oil and gas prices) and predict future crises (inflationary, food insecurity, or energy-related) for various countries.



Tools: Python, pandas, NumPy, matplotlib, seaborn.


 



Output: Predictions exported to crisis_predictions.csv, including crisis probability, type, and affected countries.

Notebooks




crisispridiction.ipynb:





-Loads and preprocesses data from four Excel files: cleaned_bulk_data_cross_cutting.xlsx, cleaned_bulk_data_food.xlsx, cleaned_bulk_data_energy.xlsx, and cleaned_bulk_data_finance.xlsx.



-Merges indicators (e.g., inflation rates, FAO food price index, oil/gas prices) with country metadata.



-Performs feature engineering (e.g., lagged variables, z-scores) and statistical crisis detection.



-Predicts crises for June–December 2025, identifying high-probability countries (e.g., CHE, JOR, OMN, PAN).



-Exports predictions to crisis_predictions.csv.


analysis.ipynb:





-Loads the same Excel files to analyze country metadata (e.g., development status, regions).



-Merges and cleans country data across food, cross-cutting, energy, and finance datasets.



-Verifies consistency in development status classifications (all 188 countries are consistent).



-Visualizes distributions of development status and regions using matplotlib and seaborn.



-Provides insights into regional and economic disparities.


Datasets

-cleaned_bulk_data_cross_cutting.xlsx : Dataset containing GDP and inflation rates of countries

-cleaned_bulk_data_energy : Dataset containing Gas and Oil prices of countries

-cleaned_bulk_data_finance : Dataset containing financial data of countries

-cleaned_bulk_data_food.xslx : Dataset containing food prices, food price index of countries

-inflation_by_development_status.csv : Dataset containing inflation rate of countries

Tools used 
