# Housing Price Prediction Modelling

This repository contains the dataset and models used for predicting house prices using machine learning techniques. The dataset is sourced from Kaggle's [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) competition.

## Dataset Information

The dataset contains details of residential properties in Ames, Iowa, and the goal is to predict the sale prices of homes based on various features.

### Data Source:
- [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

### Dataset Files:

The following files are included in this repository:

1. **data_description.txt**  
   Contains descriptions for each column/feature in the dataset.

2. **sample_submission.csv**  
   A sample submission file showing how to format predictions for submission to Kaggle.

3. **test.csv**  
   The test set (features only, no target variable). This file is used for making predictions.

4. **train.csv**  
   The training set, which contains both features and the target variable (`SalePrice`). This is used to train your model.

### File Location:

You can access the dataset files at this location in the repository:  
[https://github.com/RuvaS20/Housing-Price-Prediction-Modelling/tree/main/house-prices-advanced-regression-techniques](https://github.com/RuvaS20/Housing-Price-Prediction-Modelling/tree/main/house-prices-advanced-regression-techniques)

## Usage Instructions

To get started with the dataset:

1. Clone this repository:
   ```bash
   git clone https://github.com/RuvaS20/Housing-Price-Prediction-Modelling.git
   ```

2. Navigate to the directory where the data is stored:
   ```bash
   cd Housing-Price-Prediction-Modelling/house-prices-advanced-regression-techniques
   ```

## About the Model

The goal is to predict the `SalePrice` of houses using various machine learning models, including:
- Linear Regression
- Random Forests (RFs)
- Gradient Boosting Machines

Feature engineering and model tuning are part of the workflow to improve prediction accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
