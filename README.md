# Dengue Disease Prediction for Sri Lanka

## Overview

This research investigates an LSTM-based dengue forecasting approach for Sri Lanka using historical dengue incidence, meteorological variables, and population information.

The study focuses on improving the data preprocessing and temporal feature construction pipeline and evaluating whether these improvements increase dengue forecasting accuracy.

## Research Questions

1. Can improved temporal data preprocessing, missing-value handling, and monthly feature construction improve the accuracy of an LSTM-based dengue forecasting model for Sri Lanka?

2. Which environmental and temporal factors contribute most strongly to the final dengue predictions?

## Data

The study uses data from 2010–2024, including:

- Dengue cases
- Rainfall
- Temperature
- Humidity
- Wind speed
- Population
- Population density

## Research Workflow

Raw Data  
→ Data Validation  
→ Geographic Standardization  
→ Monthly Conversion  
→ Missing-Value Analysis  
→ Imputation Experiments  
→ Dataset Integration  
→ Exploratory Data Analysis  
→ Temporal Feature Engineering  
→ Time-Based Data Split  
→ Fixed LSTM  
→ Grey Wolf Optimization  
→ Final Evaluation  
→ Explainable AI

## Notebook Execution Order

1. `01_data_inventory.ipynb`
2. `02_dengue_data_validation.ipynb`
3. `03_geography_standardization.ipynb`
4. `04_dengue_monthly_conversion.ipynb`
5. `05_weather_data_preparation.ipynb`
6. `06_population_data_preparation.ipynb`
7. `07_missing_value_analysis.ipynb`
8. `08_imputation_experiments.ipynb`
9. `09_dataset_integration.ipynb`
10. `10_exploratory_data_analysis.ipynb`
11. `11_temporal_feature_engineering.ipynb`
12. `12_time_series_split.ipynb`
13. `13_fixed_lstm.ipynb`
14. `14_gwo_optimization.ipynb`
15. `15_final_evaluation.ipynb`
16. `16_explainable_ai.ipynb`

## Status

Research implementation in progress.