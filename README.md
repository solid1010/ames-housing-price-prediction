# Ames Housing Price Prediction: A Comprehensive Data Science Pipeline

> **🚧 Project Status:** This project is currently in active development. The current version establishes a baseline through exploratory data analysis and linear modeling.

This project demonstrates a full machine learning pipeline to predict residential home prices in Ames, Iowa. It focuses heavily on **Feature Engineering** and **Regression Benchmarking** to establish a high-performance baseline.

## Key Highlights
* **Advanced Feature Engineering:** Engineered high-impact features such as `TotalSF` (Total Square Footage), `HouseAge`, `Total Bath`, and `TotalPorchSF` to capture house characteristics from the raw data.
* **Data Preprocessing:** Implemented a robust cleaning strategy by handling missing values through logical imputation (e.g., mapping specific category "NA" values to "None") and analyzing distribution skews.
* **Target Transformation:** Applied Log-Transformation to the `SalePrice` to normalize the distribution and improve the performance of linear regression models.
* **Benchmarking:** Established performance baselines using **Ridge** and **Lasso Regression** with automatic hyperparameter tuning via Cross-Validation.
* **Performance:** Achieved an RMSE of approximately **0.13** on log-transformed prices.

## Technologies Used
* **Data Manipulation:** Python (Pandas, NumPy)
* **Visualization:** Seaborn, Matplotlib
* **Machine Learning:** RidgeCV
