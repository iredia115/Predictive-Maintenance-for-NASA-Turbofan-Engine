# Predictive-Maintenance-for-NASA-Turbofan-Engine
## Project Overview

Predictive maintenance has become a critical technology across the aviation, manufacturing, and energy industries. Instead of replacing components on a fixed schedule or waiting until failure occurs, predictive maintenance estimates the Remaining Useful Life (RUL) of equipment so maintenance can be performed only when necessary.

This project implements a complete machine learning workflow for predicting the Remaining Useful Life (RUL) of aircraft turbofan engines using NASA's C-MAPSS simulation dataset.

The objective is to train regression models capable of estimating the number of operating cycles remaining before engine failure using historical sensor measurements collected throughout each engine's degradation process.

## Background

The dataset used in this project was generated using NASA's Commercial Modular Aero-Propulsion System Simulation (C-MAPSS), a high-fidelity turbofan engine simulator developed under NASA's Integrated Vehicle Health Management (IVHM) Program.

Instead of collecting decades of real engine failure data—which would be extremely expensive and time-consuming—NASA developed a digital twin capable of simulating realistic engine degradation under varying flight conditions.

This provides researchers with realistic sensor data for developing predictive maintenance algorithms.

## Dataset

Dataset:

- NASA C-MAPSS FD001

### Contains:

- Multiple simulated turbofan engines
- Multiple operating cycles per engine
- 21 sensor measurements
- 3 operational settings
- True Remaining Useful Life (RUL)
- Project Workflow
- Data loading
- Data exploration
- Feature engineering
- Remaining Useful Life calculation
- RUL clipping
- Feature scaling
- Model training
- Hyperparameter tuning
- Model evaluation
- Performance comparison
- Machine Learning Models

## Implemented models include:

- Random Forest Regressor
- Support Vector Regression (SVR)
- Extreme Gradient Boosting (XGBoost)

Hyperparameter tuning was performed using GridSearchCV and RandomizedSearchCV.

## Skills Demonstrated
- Predictive Maintenance
- Remaining Useful Life (RUL) Estimation
- Feature Engineering
- Data Visualization
- Hyperparameter Optimization
- Regression Modeling
- Cross Validation
- Machine Learning Pipelines
- Engineering Data Analytics


## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook


## Engineering Concepts Covered
- Turbofan Engine Degradation
- Aircraft Engine Health Monitoring
- Reliability Engineering
- Condition-Based Maintenance (CBM)
- Prognostics and Health Management (PHM)
- Digital Twins
- NASA C-MAPSS Simulation
- Integrated Vehicle Health Management (IVHM)


## References
- NASA C-MAPSS Dataset
- Saxena et al. (2008), Damage Propagation Modeling for Aircraft Engine Run-to-Failure Simulation
