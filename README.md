# Bike Rental Prediction

## Project Overview
This project uses machine learning regression techniques to predict the daily number of bike rentals based on historical rental data, weather conditions, and calendar-related features.

## Problem Statement
Accurately estimating daily bike rental demand can help bike-sharing businesses plan bicycle availability and improve operational efficiency.

## Dataset
The project uses the Bike Sharing Dataset, containing daily rental information, weather conditions, and calendar features.

The target variable is `cnt`, representing the total number of bike rentals per day.

## Data Preparation
- Converted the date column to datetime format.
- Checked for missing values and duplicate records.
- Created additional calendar features, including day, day of year, and weekend.
- Separated input features and the target variable.
- Split the data into training and testing sets.

## Models Evaluated
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

## Best Model
Gradient Boosting Regressor.

### Test Results
| Metric | Score |
|---|---:|
| MAE | 447.36 |
| RMSE | 625.31 |
| R² Score | 0.9025 |

The model achieved an R² score of approximately 90.25% on the test set.

## Key Findings
- Gradient Boosting performed best among the evaluated models.
- Calendar and weather-related features help explain variations in daily bike rental demand.
- The model provides a useful baseline for predicting daily rental demand.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Project Files
- `Bike Rental Prediction.ipynb` — Data analysis, feature engineering, model training, and evaluation.
- `bike_rental_gradient_boosting.pkl` — Saved trained model.
- `day.csv` — Dataset, if included in the repository.

## Future Improvements
- Add actual-versus-predicted visualizations.
- Perform further feature analysis.
- Build an interactive prediction application.
- Evaluate the model on new data.

## Author
Darshan Bharne
