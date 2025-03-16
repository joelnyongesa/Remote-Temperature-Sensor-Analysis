# Remote-Temperature-Sensor-Analysis

## Project Overview
This project analyzes temperature data collected from four remote sensors (T1-T4) to monitor variations over time. The analysis focuses on ensuring temperatures remain within the ideal operational range (27-30°C) to protect electrical components. The Jupyter notebook includes data preprocessing, visualization, and timezone adjustments for insights into daily temperature trends.

![Temperature Trends Visualization](https://via.placeholder.com/600x400 "Hourly Temperature Trends")

## Features
- **Data Preprocessing**: Handles datetime conversion, timezone adjustments, and missing value checks.
- **Statistical Analysis**: Calculates average temperatures across sensors.
- **Visualization**: Generates time-series plots to identify trends and outliers.
- **Resampling**: Aggregates data to hourly averages for smoother trend analysis.

## Technologies Used
- **Python Libraries**: 
  - `pandas` for data manipulation
  - `matplotlib`/`seaborn` for visualization
  - `numpy` for numerical operations
- **Data Format**: Excel (`.xlsx`)

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone git@github.com:joelnyongesa/Remote-Temperature-Sensor-Analysis.git
   ```
2. **Install Dependencies**
  ```bash
    pip install pandas matplotlib seaborn numpy openpyxl
  ```
3. **Prepare the data by placing the `remote_temperature_monitoring.xlsx` file in the project's root directory**
4. **Run the Notebook using Jupyter Notebook**

## Key Steps:
1. **Data Loading** to import the temperature data from Excel.
2. **Preprocessing**, which involves converting datetime strings to proper datetime objects, and adjusting UTC timestamps to EAT.
3. **Feature Engineering**, computing the `average temperature` from T1-T4 sensors.
4. **Visualization** of the hourly temperature trends for all sensors, identifying instances where temperatures exceeded 30°C.

## Results.
1. **Critical Findings** - Time periods where temperatures risk damaging components.
2. **Trends** - Daily patterns and sensor consistency.
3. **Outputs** - Visualizations and summary statistics.
