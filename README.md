# Rotary Blower Predictive Maintenance Thesis Code

This repository contains the Python code used for the thesis project on optimizing OEM-based preventive maintenance schedules for rotary blowers using predictive analytics and integrated operational and environmental data.

## Project overview

The study evaluates whether predictive maintenance models can support more adaptive maintenance scheduling for rotary blowers compared with fixed OEM-based preventive maintenance intervals. The code includes synthetic operational data generation, environmental data integration, degradation modelling, remaining useful life prediction, maintenance classification and maintenance policy comparison.

## Repository contents

- Synthetic rotary blower data generation
- Environmental data integration
- Exploratory data analysis
- Feature engineering
- RUL prediction using Random Forest and XGBoost
- Maintenance classification
- Maintenance policy comparison
- Figure and result generation for the thesis

## Data note

The operational dataset used in this study was synthetically generated for simulation purposes. Real environmental data was integrated into the dataset to represent site-specific environmental exposure. The results should therefore be interpreted as proof-of-concept modelling results rather than field-validated predictive maintenance performance.

## Requirements

The code was developed in Python and uses common data science libraries, including:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

The required packages can be installed using:

pip install -r requirements.txt

## How to use

Clone the repository and run the notebooks or Python scripts in the order used for the thesis workflow:

1. Generate or load the modelling dataset.
2. Perform exploratory data analysis.
3. Train and evaluate the RUL prediction models.
4. Run the maintenance classification model.
5. Compare OEM-based and predictive maintenance policies.

## Author

Genuine Mapetere

## Thesis Context

This repository supports the thesis titled:

Optimisation of OEM-based preventive maintenance schedules for rotary blowers using predictive analytics and integrated operational and environmental data