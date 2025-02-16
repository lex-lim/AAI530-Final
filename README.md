# AAI530-Final
# Bike Rental Demand Prediction
This project explores bike rental demand prediction using machine learning models, specifically LSTM (Long Short-Term Memory) for time-series forecasting and SVM (Support Vector Machine) for classification. The goal is to analyze rental patterns based on factors such as weather, seasonality, and time of day to improve demand forecasting.

# Project Overview
LSTM Model: Used for time-series forecasting to predict future rental demand.

SVM Model: Used for binary classification (high vs. low demand) based on historical data and external factors.

Feature Engineering: Extracted key temporal and weather-based features for improved model performance.

Model Evaluation: Assessed performance using accuracy, precision-recall curves, and confusion matrices.

Data Visualization: Generated heatmaps and feature importance plots for insights into demand patterns.

# Install & Run Model
git clone https://github.com/yourusername/bike-rental-prediction.git  
cd bike-rental-prediction  

pip install -r requirements.txt  

python lstm_model.py  

python svm_model.py  

# Results
LSTM Model: Effective for capturing time-series trends in rental demand.

SVM Model: Achieved 88.12% accuracy in classifying high vs. low demand.

Feature Importance Analysis: Weather conditions and seasonal trends significantly impact rental demand.

# Future Improvements
Combine LSTM and SVM for a hybrid predictive approach.

Explore additional external factors like public holidays and events.

Optimize hyperparameters for improved performance.

# License
This project is licensed under the MIT License.
