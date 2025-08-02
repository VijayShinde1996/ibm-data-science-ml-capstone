# ibm-data-science-ml-capstone
This project focuses on predicting the successful landing of SpaceX's Falcon 9 first stage. The project is structured as a complete data science pipeline, from data collection to model deployment.
## SpaceX Falcon 9 First Stage Landing Prediction

## Project Structure

1. **Data Collection**
   - `1-data-collection-api.ipynb`: Collecting data using the SpaceX API
   - `2-data-collection-webscraping.ipynb`: Web scraping additional SpaceX data
   - `spacex_web_scraped.csv`: Data collected through web scraping

2. **Data Processing**
   - `3-data-wrangling.ipynb`: Data cleaning and preparation
   - `4-eda-dataviz.ipynb`: Exploratory Data Analysis with visualizations
   - `4_2-eda-sql.ipynb`: SQL-based data exploration

3. **Interactive Visualizations**
   - `5-dash-app.py`: Dashboard application for data visualization
   - `6-folium-map.ipynb`: Interactive maps showing launch sites
   - `spacex_launch_geo.csv`: Geographic data for launches
   - `spacex_launch_dash.csv`: Processed data for dashboard

4. **Machine Learning**
   - `7-predictive-models.ipynb`: Development and evaluation of ML models

## Dependencies

Requirements are listed in:
- `requirements.txt`: Python package dependencies
- `pyproject.toml`: Project configuration
- `shell.nix`: Development environment setup

## Visualizations

The `diagrams/` directory contains various visualizations including:
- Data collection workflow
- EDA insights
- Interactive maps
- ML model results

## Database

- `my_data1.db`: SQLite database containing project data

## Documentation

- `ibm-data-science-ml-project.pdf`: Detailed project documentation
- `ibm-data-science-ml-project.pptx`: Project presentation
