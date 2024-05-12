# Bike Rental Duration Prediction

## Project Overview
This project focuses on predicting the duration of bike rentals in London using historical bike rental data. The goal is to leverage features such as rental start and end stations, bike models, and time of rental to forecast the total duration of each rental.

## Dataset
The dataset includes information about bike rentals, including start and end times, stations, and bike models. Key features used in this analysis include:
- Start Station
- End Station
- Bike Model
- Start Time (Hour of the day)
- Day of the Week

## Features and Target Variable
- **Features**: Start and end station identifiers, bike model, hour of the day, day, and day of the week.
- **Target Variable**: Total duration of the bike rental in seconds (`Total duration (s)`).

## Model
The model used in this project is a RandomForestRegressor, chosen for its robustness and effectiveness in handling nonlinear relationships and interactions between features.

### Configuration
- Number of estimators: 100
- Random state: 42 (for reproducibility)

## Performance Metrics
- **Mean Squared Error (MSE)**: Measures the average of the squares of the errors.
- **R-squared (R²)**: Represents the proportion of variance for the dependent variable that's explained by the independent variables in the model.
- **Mean Absolute Error (MAE)**: The average absolute difference between the observed and predicted values.

## Requirements
This project is implemented using Python, and dependencies include:
- pandas
- numpy
- scikit-learn
- matplotlib (optional for additional visualization)

## Setup Instructions
1. Clone this repository.
2. Ensure you have Python installed on your machine.
3. Install the required packages using:
```bash
pip install pandas numpy scikit-learn matplotlib
```
4. Run the script to train the model and see the predictions.

## Usage
After setting up the environment and dependencies, you can run the main script to train the model and evaluate its performance. Modify the paths to the dataset as needed to fit your local setup.

## Contributions
Contributions to this project are welcome. You can improve the model, add features, or enhance the data preprocessing steps.

## Contact
For any queries or further information, please contact Zzl85199 Gmail:jonathan40507@gmail.com.
