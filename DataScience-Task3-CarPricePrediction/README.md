# Car Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the selling prices of used cars using Machine Learning regression techniques.

The model uses various car-related features, including brand, car age, mileage, engine capacity, maximum power, fuel type, transmission and ownership details, to estimate the selling price.

Two regression algorithms, Linear Regression and Random Forest Regressor, are implemented and evaluated to identify the best-performing model.

## Objectives

- Understand and explore the used car dataset.
- Clean the dataset by handling missing values and duplicate records.
- Perform feature engineering to extract useful information.
- Conduct Exploratory Data Analysis (EDA).
- Prepare categorical variables using One-Hot Encoding.
- Build and evaluate regression models.
- Compare model performance and identify the best-performing model.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

**Dataset Name:** Car details v3.csv

The dataset contains information about used cars, including:

- Car Name and Brand
- Manufacturing Year
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Details
- Mileage
- Engine Capacity
- Maximum Power
- Number of Seats

**Initial Dataset Size:** 8,128 rows × 13 columns

**Final Cleaned Dataset Size:** 6,926 rows × 12 columns

## Project Workflow

1. **Data Loading and Inspection** – Importing libraries and understanding the dataset.
2. **Data Cleaning** – Removing duplicates, converting measurement columns and handling missing values.
3. **Feature Engineering** – Creating car age and extracting car brands.
4. **Exploratory Data Analysis** – Visualizing selling price distributions and relationships between features.
5. **Feature Correlation Analysis** – Understanding relationships between numerical variables.
6. **Data Preprocessing** – Removing unnecessary columns and encoding categorical variables.
7. **Train-Test Split** – Dividing the dataset into 80% training and 20% testing data.
8. **Model Building** – Training Linear Regression and Random Forest Regressor.
9. **Model Evaluation** – Comparing models using MAE, RMSE and R².
10. **Feature Importance Analysis** – Identifying the most influential features.

## Machine Learning Models

The following regression algorithms were implemented:

- Linear Regression
- Random Forest Regressor

## Model Performance Comparison

| Evaluation Metric | Linear Regression | Random Forest Regressor |
| ----------------- | ----------------: | ----------------------: |
| MAE               |        140,172.15 |               72,638.14 |
| RMSE              |        274,765.73 |              128,585.49 |
| R² Score          |            0.6558 |                  0.9246 |

### Best Performing Model: Random Forest Regressor

The Random Forest Regressor achieved the best performance with:

- **MAE:** ₹72,638.14
- **RMSE:** ₹1,28,585.49
- **R² Score:** 0.9246 (92.46%)

The model explains approximately 92.46% of the variation in used car selling prices on the test dataset.

## Feature Importance Analysis

Feature importance analysis was performed using the trained Random Forest Regressor.

The most influential features include:

1. Maximum Power
2. Car Age
3. Kilometers Driven
4. Mileage
5. Engine Capacity

Maximum power was identified as the most influential feature in predicting used car prices.

## Project Structure

```text
DataScience-Task3-CarPricePrediction/
│
├── Car_Price_Prediction.ipynb
├── Car details v3.csv
└── README.md
```

## Conclusion

This project demonstrates the application of Machine Learning regression techniques to predict used car selling prices.

After performing data preprocessing, feature engineering, exploratory data analysis and model evaluation, the Random Forest Regressor was identified as the best-performing model with an R² score of 0.9246.

The project also highlights the important factors influencing used car prices through feature importance analysis.

---

**Internship:** Data Science Internship – OASIS INFOBYTE

**Task:** Task 3 – Car Price Prediction with Machine Learning
