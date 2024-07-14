# House Pricing Prediction

This project predicts house prices using a machine learning model trained on a dataset of house features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Results](#results)

## Introduction
House pricing prediction is essential for real estate and finance sectors. This project uses machine learning techniques to predict house prices based on various features.

## Dataset
The dataset includes features such as:
- Location coordinates (`long`, `lat`)
- Size metrics (`sqft_living`, `sqft_lot`)
- Number of bedrooms and bathrooms
- Number of floors, waterfront status, view quality, condition, grade
- Square footage above and below ground (`sqft_above`, `sqft_basement`)
- Year built and year renovated
- ZIP code
- House price (target variable)

## Installation
To run this project, install the required libraries:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install these dependencies using:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Usage
1. **Data Preparation**: Load the dataset, handle missing values, and split the data into training and testing sets.
2. **Model Training**: Train a machine learning model (e.g., RandomForestRegressor) on the training data.
3. **Model Evaluation**: Evaluate the model using metrics like R² score and Mean Absolute Error, and visualize the results.

## Results
The model achieved an R² score of 0.8513 and a Mean Absolute Error of 73879.0146. The scatter plot of actual vs. predicted prices demonstrates the model's performance, with a reference line indicating perfect predictions.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## Kaggle Notebook
For more details and to view the notebook, visit the [Kaggle Notebook](https://www.kaggle.com/code/sahiltripathy/house-prediction).
