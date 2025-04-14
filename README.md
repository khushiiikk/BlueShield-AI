# BlueShield-AI
AI-powered flood forecasting system leveraging atmospheric and hydrological data for early warning and disaster resilience.

📌 Overview
BlueShield AI integrates advanced feature engineering, ensemble learning techniques (like Random Forest), and spatial hydrology data to predict:

Flood Severity Levels (None, Above Normal, Severe, Extreme)

Binary Flood Occurrence (Yes / No)

With over 4,500 real flood events and 100+ geographic features, the model achieves >99% accuracy and a Nash-Sutcliffe Efficiency (NSE) of 0.9993, showing outstanding predictive capability.

🧠 Core Features
🚨 Predict flood occurrence based on historical rainfall and hydrology

🔍 Classify severity of upcoming floods with near-perfect accuracy

📊 Uses spatial and temporal precipitation trends

🛰️ Works with catchment characteristics, gauge metadata, and rainfall sequences

🔁 Implements cross-validation and model comparisons

🧪 Evaluation metrics include MSE, RMSE, F1-score, NSE, and more

🔬 Datasets Used
floodevents_indofloods.csv – Historic flood parameters (Peak discharge, volume, etc.)

precipitation_variables_indofloods.csv – Rainfall over 10 days before each flood

catchment_characteristics_indofloods.csv – Hydrological and geological data

metadata_indofloods.csv – Station-specific warning levels and coordinates

Preprocessed files are saved as:

processed_flood_events.csv

processed_precipitation.csv

processed_catchment.csv

processed_metadata.csv

🧮 Model Highlights
Random Forest Classifier for multi-class and binary classification

Feature importance via Mutual Information

Cross-validation accuracy: 99.7%

Test accuracy: 100% (on hold-out data)

NSE (Flood Severity): 0.9993

📈 Evaluation Metrics
Classification: Accuracy, Precision, Recall, F1-score

Regression style check: MSE, RMSE

Hydrological fit: Nash-Sutcliffe Efficiency (NSE)

Confusion Matrix Visualization with Seaborn

📦 Getting Started
Prerequisites
Python 3.8+

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Run the model
bash
Copy
Edit
python flood_model.py


