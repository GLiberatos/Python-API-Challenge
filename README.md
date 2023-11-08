# Weather Data Analysis and Vacation Planner

  # Weather Data Analysis Project

  ## Overview:
  This project utilizes the OpenWeatherMap API to retrieve weather data for random cities and examines the relationships between city latitude and various weather parameters. It generates scatter and linear regression    plots to visualize these relationships.

  ### Files:
   - weather_data_analysis.ipynb: Jupyter Notebook containing Python code.
   - output_data/: Directory containing output data and plots.

  ### Dependencies:
   - Python 3.x
   - Jupyter Notebook
   - Libraries: Matplotlib, Pandas, NumPy, Requests, SciPy, citipy

  ### Usage:
   - Clone this repository and navigate to the project directory.
   - Install the required dependencies using pip.
   - Open the weather_data_analysis.ipynb file in Jupyter Notebook and execute the code cells.
   - Plots will be saved in the output_data/ directory.

  ### Results:
   - Analyzes how weather parameters vary with latitude.
   - Visualizes trends using scatter plots and regression analysis.

# VacationPy

## Overview:
VacationPy is a Python script that assists in vacation planning by providing weather data for cities worldwide. You can filter cities based on your preferred weather conditions and discover nearby hotels.

### Features:
 - Fetches weather data from various cities.
 - Filters cities based on user-defined weather preferences.
 - Identifies and displays nearby hotels using the Geoapify API.

### How to Use:
 - Run the WeatherPy.ipynb Jupyter Notebook to obtain weather data for a list of cities.
 - Utilize the data to filter cities according to your desired weather conditions.
 - The script will locate and showcase nearby hotels in the chosen cities.

### Dependencies:
 - Python libraries: pandas, requests, hvplot.pandas
 - Geoapify API Key (required for hotel data retrieval)

### Installation:
 - Clone this repository to your local machine.
 - Replace your_api_key_here in the api_keys.py file with your actual Geoapify API key.
 - Open and run the Jupyter Notebook WeatherPy.ipynb.
 - Follow the instructions in the notebook to plan your vacation.

### Note:
 - Ensure the security of your API key and do not share it publicly.
 - Customize the weather conditions to align with your preferences.
