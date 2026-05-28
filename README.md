# House Price Prediction using Linear Regression

## Project Overview

This project predicts house prices using Machine Learning. A Linear Regression model was developed using Python and Scikit-Learn after performing data preprocessing, feature engineering, exploratory data analysis, and model evaluation.

The objective of this project was to understand the complete machine learning workflow, from raw data preparation to predictive modeling and performance evaluation.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## Dataset

The dataset contains various housing-related features that influence the final selling price of a property.

### Features

- MSSubClass (Building Class)
- MSZoning (Zoning Classification)
- LotArea (Lot Size)
- LotConfig (Lot Configuration)
- BldgType (Building Type)
- OverallCond (Overall Condition)
- YearBuilt (Construction Year)
- YearRemodAdd (Remodel Year)
- Exterior1st (Exterior Covering)
- BsmtFinSF2 (Finished Basement Area)
- TotalBsmtSF (Total Basement Area)

### Target Variable

- SalePrice (House Selling Price)

The objective of this project is to predict the SalePrice of a house based on its characteristics and property features.

---

## Project Workflow

### 1. Data Loading

The dataset was loaded and explored using Pandas to understand its structure and features.

### 2. Data Cleaning

- Removed unnecessary columns
- Checked for missing values
- Prepared the dataset for machine learning

### 3. Exploratory Data Analysis (EDA)

- Analyzed feature distributions
- Studied relationships between variables
- Generated correlation heatmaps
- Identified important features affecting house prices

### 4. Feature Engineering

- Applied One-Hot Encoding to categorical features
- Converted categorical variables into numerical format

### 5. Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

### 6. Model Training

A Linear Regression model from Scikit-Learn was trained using the processed dataset.

### 7. Model Evaluation

The model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

---

## Results

The model performance metrics are shown below.



- R² Score: See model_results.png
- MAE: See model_results.png
- RMSE: See model_results.png
- MAPE: See model_results.png

---

## Visualizations

### Dataset Preview

The dataset preview provides an overview of the available features and target variable used for prediction.

---

### Correlation Heatmap
The correlation heatmap visualizes the relationships between numerical features in the dataset.

#### Observations

- Darker colors indicate stronger correlations.
- Features with higher positive correlation to SalePrice have a stronger influence on house prices.
- The heatmap helps identify important features for prediction.

---

### Distribution of House Prices

This histogram shows how house prices are distributed across the dataset and helps identify common price ranges.

---

### Actual vs Predicted Prices

This scatter plot compares actual house prices with model predictions.

#### Observations

- Points closer to the trend line indicate better predictions.
- Points farther away indicate prediction errors.
- The model captures the overall trend of house prices reasonably well.

---

### Model Performance

The model evaluation metrics demonstrate the effectiveness of the Linear Regression model in predicting house prices.

---

## Key Skills Demonstrated

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Feature Engineering
- Linear Regression
- Model Evaluation
- Data Visualization
- Machine Learning Workflow
- Predictive Modeling

---

## Project Structure

```text
house-price-prediction-linear-regression
│
├── house_price_predictor.ipynb
├── README.md
├── requirements.txt
│
├── data
│   └── HousePricePrediction.csv
│
└── images
    ├── dataset_preview.png
    ├── correlation_heatmap.png
    ├── saleprice_distribution.png
    ├── actual_vs_predicted.png
    └── model_results.png
```

## Future Improvements

Possible enhancements include:

- Random Forest Regression
- XGBoost Regression
- Hyperparameter Tuning
- Advanced Feature Selection
- Streamlit Deployment
- Flask Deployment

---

## Author

Sneha Pandey

MCA Student | Machine Learning Enthusiast

This project was created as part of my Machine Learning learning journey and placement preparation.
