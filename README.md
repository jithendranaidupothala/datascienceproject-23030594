# Predicting Crop Yield Using Machine Learning Models 🌾

This repository contains the code and analysis for the MSc Data Science final project focused on predicting rice crop yield using machine learning techniques for precision agriculture in India.

## Project Overview

This project investigates how ML models like Linear Regression, Random Forest, and XGBoost can be used to predict rice crop yields using features such as rainfall, area under cultivation, fertilizers, pesticides, and production data.

Key goals:
- Accurately predict rice yield from agricultural and climate data.
- Identify the most influential features impacting yield.
- Support farmers and stakeholders in data-driven decision-making.

## Dataset

- Source: [Data.World](https://data.world/thatzprem)
- Rows: 15,104 records
- Features: 11 columns (e.g., State, District, Season, Crop Year, Area, Production, Rainfall)
- Target: Yield (Production per Area)
- License: Creative Commons CC BY 4.0

## Machine Learning Models

- Linear Regression
- Random Forest
- XGBoost (with Hyperparameter Tuning)

All models were trained using:
- Train-test split (80/20)
- Feature scaling
- Label encoding for categorical variables

###Performance Metrics

| Model              | R² Score | MSE   |
|--------------------|----------|-------|
| Linear Regression  | 0.38     | 0.59  |
| Random Forest      | 0.87     | 0.12  |
| XGBoost (Untuned)  | 0.91     | 0.08  |
| XGBoost (Tuned)    | 0.90     | 0.09  |

##Visualizations

Key EDA plots included:
- Fertilizer Use vs Yield
- Season vs Production
- State-wise Yield Distribution
- Area vs Production/Yield
- Heatmaps, KDE plots, Pairplots

##Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Seaborn, Matplotlib

##How to Run

```bash
git clone https://github.com/jithendranaidupothala/datascienceproject-23030594
cd datascienceproject-23030594
# Open and run the notebook or Python scripts
