# Housing-Price-Prediction-Using-PySpark

# Project Summary
This project aims to predict housing prices in California districts based on various features such as location coordinates, housing age, room count, population, household count, and median income. By leveraging machine learning algorithms, we intend to preprocess the dataset to handle missing values and outliers. Subsequently, we will explore feature engineering techniques to enhance model performance. The primary objective is to develop a robust predictive model that accurately estimates value of the house. This predictive capability can aid home buyers, sellers, and real estate agents in making informed decisions.

## Dataset Description
The dataset comprises information about houses in a specific California district, along with summary statistics derived from the 1990 census data. The dataset requires preprocessing due to its unclean nature. The dataset includes the following columns:

*Dataset Source* - https://www.kaggle.com/datasets/camnugent/california-housing-prices

1. `longitude`: Represents the westward position of a house.
2. `latitude`: Indicates the northward position of a house.
3. `housingMedianAge`: Median age of houses within a block.
4. `totalRooms`: Total number of rooms within a block.
5. `totalBedrooms`: Total number of bedrooms within a block.
6. `population`: Total number of people residing within a block.
7. `households`: Total number of households within a block.
8. `medianIncome`: Median income for households within a block.
9. `medianHouseValue`: Median house value for households within a block.
10. `oceanProximity`: Indicates the proximity of the house to the ocean/sea.

## Research Questions
1. Can we predict the median house value based on other features in the dataset?
2. How does the median income correlate with other housing characteristics?

## Model Design
We plan to apply machine learning models to analyze and predict housing characteristics. Specifically, we aim to utilize regression algorithms due to the nature of the prediction task. Two algorithms will be employed and compared:

1. **Linear Regression**: A baseline model to establish a simple relationship between input features and the target variable.
2. **Random Forest Regression**: A more complex ensemble learning technique to capture non-linear relationships and interactions among features.

## Dataset Characteristics
- **Number of Instances**: 20640
- **Number of Features**: 10
- **Feature Types**: The features include both numerical and categorical variables.
    - Numerical Features: `longitude`, `latitude`, `housingMedianAge`, `totalRooms`, `totalBedrooms`, `population`, `households`, `medianIncome`, `medianHouseValue`
    - Categorical Feature: `oceanProximity`
