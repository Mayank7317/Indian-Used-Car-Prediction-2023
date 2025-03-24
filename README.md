# Indian Used Car Price Prediction 2023

This project aims to predict the prices of used cars in India using machine learning techniques. The dataset used for this project is `usedCars.csv`.

## Project Structure

```
Indian Used Car Prediction 2023.ipynb
usedCars.csv
.ipynb_checkpoints/
    Indian Used Car Prediction 2023-checkpoint.ipynb
```

- `Indian Used Car Prediction 2023.ipynb`: Jupyter notebook containing the code and analysis for predicting used car prices.
- `usedCars.csv`: Dataset containing information about used cars in India.
- `.ipynb_checkpoints/`: Directory containing checkpoint files for the Jupyter notebook.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Mayank7317/Indian-Used-Car-Price-Prediction-2023.git
    cd Indian-Used-Car-Price-Prediction-2023
    ```

2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook:
    ```sh
    jupyter notebook Indian\ Used\ Car\ Prediction\ 2023.ipynb
    ```

## Usage

Run the cells in the Jupyter notebook to perform data analysis, preprocessing, and model training for predicting used car prices.

## Dataset

The dataset `usedCars.csv` contains the following columns:
- `Id`: Unique identifier for each car
- `Company`: Car manufacturer
- `Model`: Car model
- `Variant`: Car variant
- `FuelType`: Type of fuel used by the car (Petrol/Diesel/CNG)
- `Colour`: Color of the car
- `Kilometer`: Distance driven in kilometers
- `BodyStyle`: Body style of the car (Hatchback/Sedan/SUV/MPV)
- `TransmissionType`: Transmission type (Manual/Automatic)
- `ManufactureDate`: Date of manufacture
- `ModelYear`: Year of the model
- `CngKit`: Presence of CNG kit (if any)
- `Price`: Selling price of the car
- `Owner`: Number of previous owners
- `DealerState`: State of the dealer
- `DealerName`: Name of the dealer
- `City`: City of the dealer
- `Warranty`: Warranty status
- `QualityScore`: Quality score of the car
