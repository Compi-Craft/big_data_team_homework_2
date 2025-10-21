# Big Data Team Homework 2

## Project Overview

This project contains comprehensive solutions for missing data visualization and exploratory data analysis (EDA) using Airbnb datasets from Athens, Greece.

## Structure

### L6-EDA/
- **`load_athens_airbnb_data.ipynb`** - Data loading and preprocessing for Athens Airbnb data
- **`data-cleansing.ipynb`** - Data cleaning and validation procedures
- **`geo_map.ipynb`** - Geographic visualization of Airbnb listings
- **`setup.ipynb`** - Environment setup and configuration

### Missing Data Visualization
- **`Missing_Values_Visualization_Challenge.ipynb`** - Complete missing data analysis with:
  - Statistical overview of missing values
  - Missing data matrix visualization
  - Correlation analysis of missing patterns
  - Spark-based implementation for large datasets

### Documentation
- **`missing_data_visualization_summary.md`** - Comprehensive technical documentation
- **`visualization_screenshots/`** - Generated visualization outputs

## Key Features

- **Spark Integration**: Distributed processing for large datasets
- **Multi-dimensional Analysis**: Bar charts, heatmaps, and correlation matrices
- **Real-world Data**: Athens Airbnb listings with realistic missing patterns
- **Scalable Implementation**: Handles datasets with thousands of rows efficiently

## Dependencies

```bash
# For Jupyter notebooks
pip install jupyter pyspark matplotlib seaborn pandas numpy

# For Spark (if running locally)
# Install Apache Spark and configure SPARK_HOME
```

## Usage

1. **Data Loading**: Run `L6-EDA/load_athens_airbnb_data.ipynb` to load Athens Airbnb data
2. **Data Cleaning**: Execute `L6-EDA/data-cleansing.ipynb` for data validation
3. **Missing Data Analysis**: Use `Missing_Values_Visualization_Challenge.ipynb` for comprehensive missing data visualization
4. **Geographic Analysis**: Run `L6-EDA/geo_map.ipynb` for location-based insights