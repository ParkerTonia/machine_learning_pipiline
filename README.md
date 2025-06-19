# Pipeline Project

## Project Overview
This project was completed as a class assignment in my Data Science course. It taught me how to build an end-to-end data preprocessing pipeline, perform feature engineering, and apply machine learning models using Scikit-Learn. My goal was to predict apartment rental prices by handling both numeric and categorical data in a clean, reproducible workflow.

## Skills Demonstrated
- Loading and splitting data with Pandas and `train_test_split`  
- Building numeric and categorical pipelines using `SimpleImputer`, `StandardScaler`, and `OneHotEncoder`  
- Combining pipelines with `ColumnTransformer` for unified preprocessing  
- Training and evaluating Linear Regression and Random Forest models  
- Applying cross-validation and calculating RMSE and R²  
- Writing clear code comments and documentation

## Dataset
The data comes from a modified version of the Canvas-provided `apartments_for_rent.csv`, containing 10,000 apartment listings with these columns:

- **id**: unique listing identifier  
- **latitude**, **longitude**: location coordinates  
- **bathrooms**, **bedrooms**: room counts  
- **fee**, **has_photo**, **pets_allowed**: categorical features  
- **square_feet**: size in square feet  
- **price**: rental price (target)

Before running the notebook, place `apartments_for_rent.csv` in a `data/` folder at the root of the repository.

