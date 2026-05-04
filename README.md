# weather-dataset

Global Weather Repository: Analysis and Forecasting
This project performs Exploratory Data Analysis (EDA) and builds a predictive model using the Global Weather Repository dataset. The goal is to understand global weather patterns and forecast temperatures based on geographical and temporal features.

Project Overview
Data Cleaning: Handled datetime conversions and checked for missing values/duplicates.
Exploratory Data Analysis (EDA):
Distribution analysis of temperature and precipitation.
Correlation analysis of weather metrics (humidity, pressure, UV index, etc.).
Time-series visualization of average global temperatures.
Modeling: Built a Random Forest Regressor to predict temperature_celsius using features like latitude, longitude, and time-based components.
Performance: The model achieved an R-squared score of 0.97, indicating high predictive accuracy.
Dataset
The dataset includes real-time weather information from various locations globally, including:

Geographical coordinates (Latitude/Longitude)
Temperature (Celsius/Fahrenheit)
Atmospheric conditions (Pressure, Humidity, Cloud cover)
Precipitation and Wind speed
Requirements
To run the analysis locally, ensure you have the following Python libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn
How to Use
Clone the repository.
Place the GlobalWeatherRepository.csv in the project directory.
Run the Jupyter/Colab notebook to reproduce the analysis and model results.
Results
The model successfully identifies the strong relationship between location/time and temperature, providing a robust baseline for global weather forecasting.
