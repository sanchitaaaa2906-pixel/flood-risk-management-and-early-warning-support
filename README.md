# flood-risk-management-and-early-warning-support
Deep learning and GIS-based flood susceptibility mapping for Odisha, India, using rainfall, elevation, slope, and surface-water data. Built with Python, TensorFlow, Google Earth Engine, and Folium to visualize potential risk areas.
# Flood Risk Management and Early Warning Support

## Project Overview
A data science project exploring flood-risk classification using geographical data, Python, deep learning and GIS, with a focus on Odisha, India.

## Objectives
- Explore monsoon rainfall and geographical factors.
- Process elevation, slope and historical surface-water data.
- Train a neural network for proxy-label classification.
- Visualise sampled locations on an interactive map.

## Technologies
- Python
- Google Colab
- Google Earth Engine
- Pandas and NumPy
- TensorFlow / Keras
- Scikit-learn
- Folium
- Matplotlib

## Data Sources
- CHIRPS daily rainfall
- SRTM elevation
- JRC Global Surface Water

## Methodology
The notebook samples geographical data, prepares a dataset, trains a neural network, evaluates classification metrics and visualises model scores on a map.

## Limitations
The current prototype uses historical surface-water occurrence as a proxy label rather than verified flood-event records. It is not a validated operational flood forecasting or early-warning system.

## How to Run
1. Open the notebook in Google Colab.
2. Configure Google Earth Engine authentication and your Google Cloud project.
3. Run the notebook cells in order.
4. Review the generated dataset, evaluation results and map.

## Author
Sanchita Pattanayak
