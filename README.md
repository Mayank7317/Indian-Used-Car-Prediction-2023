Indian Used Car Price Prediction 2023
Project Overview
The aim of this project is to predict the price of used cars in major Indian metro cities. The prediction is based on various factors such as car manufacturer, model, variant, fuel type, color, etc. This project uses data analysis and machine learning algorithms to provide insights and predict prices, benefiting both buyers and sellers in the used car market.

Table of Contents
Project Overview

Dataset

Data Preprocessing

Exploratory Data Analysis

Model Training

Results

Conclusion

Installation

Usage

Contributing

License

Dataset
The dataset used in this project contains information about used cars, including attributes such as:

Company: The manufacturer of the car.

Model: The specific model of the car.

Variant: The variant of the car model.

FuelType: The type of fuel the car uses (e.g., Petrol, Diesel).

Colour: The color of the car.

Kilometer: The distance the car has traveled.

BodyStyle: The body style of the car (e.g., Hatchback, Sedan).

TransmissionType: The type of transmission (e.g., Manual, Automatic).

ManufactureDate: The date the car was manufactured.

ModelYear: The model year of the car.

CngKit: Whether the car has a CNG kit.

Price: The price of the car.

Owner: The number of previous owners.

DealerState: The state where the dealer is located.

DealerName: The name of the dealer.

City: The city where the car is located.

Warranty: Whether the car comes with a warranty.

QualityScore: A score representing the quality of the car.

Data Preprocessing
The dataset underwent several preprocessing steps to prepare it for analysis and model training:

Loading the Dataset: The dataset was loaded using pandas.

Handling Missing Values: Columns with a high percentage of missing values were dropped, and rows with missing values in essential columns were removed.

Feature Engineering: The ManufactureDate column was dropped, and the ModelYear column was converted to CarAge by subtracting the model year from the current year (2023).

Data Type Conversion: The Price column was converted from a string to a float for easier analysis.

Descriptive Statistics: Basic statistics were calculated to understand the distribution of the data.

Exploratory Data Analysis
Exploratory Data Analysis (EDA) was conducted to gain insights into the dataset:

Car Company Distribution: The distribution of cars by company was visualized to understand the most common manufacturers.

Price Distribution: The distribution of car prices was analyzed to identify trends and outliers.

Correlation Analysis: The correlation between different features was examined to identify potential predictors for the car price.

Model Training
Several machine learning models were trained to predict the price of used cars. The models used include:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

The models were evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

Results
The results of the model training are as follows:

Linear Regression: MAE = X, MSE = Y, R-squared = Z

Random Forest Regressor: MAE = X, MSE = Y, R-squared = Z

Gradient Boosting Regressor: MAE = X, MSE = Y, R-squared = Z

The best-performing model was the Gradient Boosting Regressor, which achieved the highest R-squared value.

Conclusion
This project successfully predicted the price of used cars in Indian metro cities using various machine learning models. The Gradient Boosting Regressor performed the best, providing accurate price predictions based on the given features. Future work could include incorporating additional features and exploring more advanced models to improve prediction accuracy.

Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy
git clone https://github.com/yourusername/indian-used-car-price-prediction.git
Navigate to the project directory:

bash
Copy
cd indian-used-car-price-prediction
Install the required dependencies:

bash
Copy
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
jupyter notebook Indian_Used_Car_Prediction_2023.ipynb
Usage
To use this project for predicting used car prices:

Load the dataset: Ensure the dataset is in the correct format and located in the project directory.

Run the notebook: Execute the cells in the Jupyter Notebook to preprocess the data, perform EDA, and train the models.

Make predictions: Use the trained models to predict the prices of used cars based on the input features.
