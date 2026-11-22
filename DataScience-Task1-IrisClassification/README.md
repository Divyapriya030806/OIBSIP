# Iris Flower Classification 🌸

## Project Overview

This project focuses on building a Machine Learning model to classify Iris flowers into three different species: Setosa, Versicolor, and Virginica based on their physical measurements.

This project was completed as part of the **OASIS INFOBYTE Data Science Internship**.

## Dataset

The Iris dataset is obtained from Scikit-learn's built-in datasets.

It contains:

- 150 flower samples
- 4 input features
- 3 target classes

### Features

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target Classes

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Imported the required Python libraries.
2. Loaded and explored the Iris dataset.
3. Performed Exploratory Data Analysis (EDA).
4. Checked for missing values and analysed statistical summaries.
5. Created pairplots and boxplots for data visualisation.
6. Analysed the importance of input features.
7. Split the dataset into 80% training and 20% testing data.
8. Trained Logistic Regression and K-Nearest Neighbours (KNN) models.
9. Evaluated both models using accuracy, confusion matrices, precision, recall, and F1-score.
10. Compared the model performances and selected the preferred model.

## Machine Learning Algorithms

### 1. Logistic Regression

A classification algorithm used to predict the flower species based on input measurements.

### 2. K-Nearest Neighbours (KNN)

A classification algorithm that predicts the species based on the nearest data points.

## Model Performance

| Algorithm           | Accuracy |
| ------------------- | -------: |
| Logistic Regression |   93.33% |
| KNN                 |   93.33% |

Both models achieved an accuracy of 93.33% on the test dataset.

Logistic Regression was selected as the preferred model because it demonstrated more balanced performance across the three species.

## Conclusion

This project helped in understanding the practical implementation of Machine Learning classification algorithms. Through data exploration, visualisation, model training, and evaluation, both models achieved 93.33% accuracy. Logistic Regression was selected as the preferred model based on its balanced classification performance.

## Project Structure

```text
DataScience-Task1-IrisClassification/
│
├── Iris_Flower_Classification.ipynb
└── README.md
```

## Internship

**Organization:** OASIS INFOBYTE  
**Domain:** Data Science  
**Task:** Iris Flower Classification
