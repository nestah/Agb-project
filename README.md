# Above Ground Biomass (AGB) Prediction using Random Forest

## Project Overview

This project aims to predict Above Ground Biomass (AGB) using satellite imagery and machine learning techniques. It utilizes data from Sentinel-1, Sentinel-2, and ALOS-2 satellites, preprocessed in Google Earth Engine (GEE), and then uses Random Forest regression in Python to create a robust prediction model.

## Features

- Data preprocessing using Google Earth Engine (GEE)
- Integration of multiple satellite data sources (Sentinel-1, Sentinel-2, ALOS-2)
- Random Forest regression model for AGB prediction implemented in Jupyter notebooks
- Comprehensive model evaluation metrics
- Visualization of results and model performance
- GeoTIFF output for predicted AGB values

## Workflow

1. **Data Preprocessing (Google Earth Engine)**
   - Acquisition and preprocessing of Sentinel-1, Sentinel-2, and ALOS-2 data
   - Calculation of various spectral indices
   - Export of processed data as GeoTIFF files

2. **AGB Prediction (Jupyter Notebook)**
   - Data loading and preparation
   - Random Forest model training and prediction
   - Model evaluation and visualization
   - Export of predicted AGB as GeoTIFF

## Requirements

- Google Earth Engine account
- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- rasterio

## Usage

### Google Earth Engine Preprocessing

1. Log in to your GEE account
2. Use the provided GEE script to preprocess satellite data
3. Export the results as GeoTIFF files

### Jupyter Notebook Analysis

1. Open the Jupyter notebook `agb_prediction.ipynb`
2. Update file paths to point to your preprocessed data
3. Run the notebook cells sequentially to:
   - Train the Random Forest model
   - Make predictions on the full dataset
   - Generate evaluation metrics and plots
   - Save the predicted AGB as a GeoTIFF file

## Output

- Predicted AGB GeoTIFF file
- Evaluation metrics (R², MSE, MAE)
- Visualization plots:
  - Actual vs Predicted AGB
  - Residual plot
  - Feature importance
  - Error distribution
  - QQ plot of prediction errors

