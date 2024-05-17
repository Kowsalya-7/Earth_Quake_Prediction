# Earthquake Prediction Project README

## Overview

This project aims to predict earthquakes using machine learning techniques. The dataset includes various features related to earthquakes such as date, time, location (latitude and longitude), type, depth, magnitude, and several other parameters. The goal is to develop a model that can accurately predict the likelihood and severity of earthquakes based on these features.

## Dataset Description

The dataset contains the following features:

1. **Date**: Date of the earthquake event.
2. **Time**: Time of the earthquake event.
3. **Latitude**: Latitude coordinate of the earthquake's epicenter.
4. **Longitude**: Longitude coordinate of the earthquake's epicenter.
5. **Type**: Type of earthquake (e.g., tectonic, volcanic).
6. **Depth**: Depth of the earthquake's focus below the Earth's surface.
7. **Depth Error**: Error in depth measurement, if available.
8. **Depth Seismic Stations**: Number of seismic stations used to determine depth.
9. **Magnitude**: Magnitude of the earthquake (measures energy released).
10. **Magnitude Type**: Type of magnitude measurement (e.g., Richter, Moment).
11. **Magnitude Error**: Error in magnitude measurement, if available.
12. **Magnitude Seismic Stations**: Number of seismic stations used to determine magnitude.
13. **Azimuthal Gap**: Gap in azimuthal coverage of seismic stations.
14. **Horizontal Distance**: Horizontal distance from epicenter to nearest seismic station.
15. **Horizontal Error**: Error in horizontal distance measurement, if available.
16. **Root Mean Square**: Measure of the quality of the seismic data.
17. **ID**: Unique identifier for each earthquake event.
18. **Source**: Source of the earthquake data.
19. **Location Source**: Source of the location data.
20. **Magnitude Source**: Source of the magnitude data.
21. **Status**: Status of the earthquake event (e.g., reviewed, automatic).

## Project Structure

- `dataset.csv/`: Directory containing the earthquake dataset.
  - `earthquake_data.csv`: Main dataset file containing earthquake records.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and modeling.
  - `1_earthquake.ipynb`: Notebook for building and evaluating machine learning models.
- `README.md`: This README file providing an overview of the project.


