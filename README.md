# Household Electric Power Consumption Forecasting using LSTM

## Project Overview
This project uses a Long Short-Term Memory (LSTM) neural network to forecast household electricity consumption using historical power consumption data.

## Dataset
- Dataset: Individual Household Electric Power Consumption
- Records used: 10,000
- Time steps: Previous 60 readings
- Target: Global Active Power (kW)

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Project Workflow
1. Load the electricity consumption dataset.
2. Handle missing values.
3. Normalize the electricity consumption data.
4. Create sequences using the previous 60 readings.
5. Split data into training and testing sets.
6. Build and train the LSTM model.
7. Predict electricity consumption on test data.
8. Evaluate the model using MAE and RMSE.
9. Plot actual vs predicted consumption.

## Model Results
- Training epochs: 10
- MAE: 0.5436 kW
- RMSE: 0.7672 kW

## How to Run
1. Open `household_electricity_lstm.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. The notebook downloads the dataset and trains the LSTM model.
4. View the predictions, evaluation metrics, and graph.

## Conclusion
The LSTM model was trained and tested using household electricity consumption data. Its predictions were compared with actual values to evaluate forecasting performance.
