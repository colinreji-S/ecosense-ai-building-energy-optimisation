#🌿 EcoSense AI — Building Energy Prediction & Optimisation

EcoSense AI is a Data Science and Machine Learning project that predicts building electricity consumption and identifies possible energy-wasting situations.

## Problem

Buildings often waste electricity because lights and cooling systems continue operating even when rooms are unoccupied.

## Solution

EcoSense AI uses temperature, humidity, occupancy, light level, and time-based data to:

- Predict electricity consumption
- Compare actual and predicted energy usage
- Detect high electricity usage in unoccupied spaces
- Estimate potential energy savings
- Estimate carbon-emission reduction
- Generate energy-saving recommendations

## Machine Learning Model

- Model: Random Forest Regressor
- Model R² Score: 0.94
- Mean Absolute Error: 0.72 kWh

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Files

- `EcoSense_AI_Building_Energy_Optimisation.ipynb` — complete project notebook
- `EcoSense_AI_results.csv` — generated energy data and model results

## Future Improvements

- Real IoT sensor integration
- Streamlit dashboard
- Real-time anomaly alerts
- HVAC and lighting-control automation
