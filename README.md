# Vehicle Insurance Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting potential insurance fraud in vehicle claims using machine learning techniques. It includes data cleaning, feature engineering, and preparation for modeling.

## Dataset
- The dataset contains policyholder information, vehicle details, and claim records.
- Categorical variables were mapped to numeric representations where appropriate to allow feature engineering.
- Textual and range-based values (e.g., "20000 to 29000" for VehiclePrice) were converted to numeric columns.

## Feature Engineering
Some of the engineered features include:
- **ClaimFrequency**: Past claims per claim filing period.
- **PolicyTenureBeforeAccident**: Duration of policy before accident.
- **VehicleDriverAgeRatio**: Vehicle age relative to driver age.
- **HighValueVehicle**: Binary indicator for high-value vehicles.
- **MultipleCarsFlag**: Binary indicator for multiple vehicle ownership.
- **FrequentAddressChange**: Binary indicator for frequent address changes.
- **ClaimSupportPresent**: Whether the claim has supporting evidence (police report or witness).
- **DriverRiskScore**: Interaction of driver rating and deductible amount.

## Project Structure
- `notebooks/` : Jupyter notebooks for cleaning, feature engineering, and analysis.
- `data/` : (Optional) Datasets (excluded from Git to avoid large files).
- `scripts/` : Python scripts for preprocessing and modeling.
- `README.md` : This file.

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/LynneMutwiri/Vehicle-Insurance-Fraud-Detection-Using-ML.git
