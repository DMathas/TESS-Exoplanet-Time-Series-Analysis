# TESS Exoplanet Time Series Analysis

This repository contains Python code for the analysis of time-series data collected by NASA's Transiting Exoplanet Survey Satellite (TESS). The project focuses on two stars with transiting exoplanets and involves astrophysics and astronomy programming.

## Project Overview

The analysis includes the following components:

1. **Data Loading**
   - TESS data is loaded from a file using the `load_tess_data` function.

2. **Data Cleaning**
   - The `clean_tess_data` function removes rows with NaN values from the raw TESS data.

3. **Data Plotting**
   - The `plot_tess_data` function visualizes unsmoothed TESS data.

4. **Data Smoothing**
   - The `smooth_lightcurve` function smooths the unsmoothed lightcurve using a rolling average window.

5. **Smoothed Data Plotting**
   - The `plot_smoothed_cleaned_data` function creates plots for smoothed and cleaned TESS data.

6. **Lomb-Scargle Periodogram**
   - The `lomb_scargle_perio` function computes and plots the Lomb-Scargle periodogram to find the orbital period.

7. **Eclipse Simulation Function**
   - The `eclipse_function` generates a simulated eclipse lightcurve based on specified parameters.

8. **Eclipse Fitting and Visualization**
   - The `fit_eclipse` function fits an eclipse model to a subset of data and visualizes the fit.
   - The `plot_data_and_fitted_model` function plots both the data and the fitted model.

## Usage

To use this code for analyzing TESS time-series data, follow these steps:

1. Load the TESS data using `load_tess_data`.
2. Clean the data using `clean_tess_data`.
3. Plot the unsmoothed data with `plot_tess_data`.
4. Smooth the data with `smooth_lightcurve`.
5. Plot the smoothed and cleaned data using `plot_smoothed_cleaned_data`.
6. Analyze the Lomb-Scargle periodogram with `lomb_scargle_perio`.
7. Simulate an eclipse using `eclipse_function`.
8. Fit an eclipse model to a subset of data and visualize the fit with `fit_eclipse` and `plot_data_and_fitted_model`.


