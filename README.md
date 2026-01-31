# Munich Traffic and Drone Air Quality Measurement Correlation

This repository contains analysis code for investigating the correlation between traffic patterns and air quality measurements collected via drone in Munich, Germany.

## Project Overview

This project analyzes the relationship between traffic data from multiple sensors and air quality measurements collected using drone-based sensors. The goal is to understand how traffic patterns influence local air quality conditions in the Munich area.

## Repository Structure

### Notebooks

- **`traffic_analysis.ipynb`**: Primary analysis of traffic data including flow, speed, and concentration from 5 traffic sensors. Includes data preprocessing, temporal analysis, and statistical exploration of traffic patterns throughout the day.

- **`drone_data_air_quality.ipynb`**: Analysis of air quality measurements collected via drone flights. Processes sensor data from multiple flight sessions, calibrates measurements, and explores spatial and temporal variations in air pollutant concentrations.

## Data

The analysis uses the following data sources (not included in this repository):

- **Traffic Data**: 5-sensor traffic measurements from September 3, 2025, including:
  - Traffic flow (vehicles per time period)
  - Traffic speed (average vehicle speeds)
  - Traffic concentration (vehicle density)

- **Air Quality Data**: Drone-collected air quality measurements from multiple flight sessions on September 3, 2025, including:
  - Particulate matter (PM2.5, PM10)
  - Gas concentrations (NO₂, CO, O₃)
  - GPS coordinates and flight timestamps

## Requirements

```
Python 3.x
pandas
numpy
matplotlib
seaborn
scipy
datetime
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Mugo95/munich-traffic-and-drone-airquality-measurement-correlation.git
   ```

2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```

3. Add your data files to the project directory (CSV and TXT files are gitignored)

4. Open and run the Jupyter notebooks:
   ```bash
   jupyter notebook traffic_analysis.ipynb
   jupyter notebook drone_data_air_quality.ipynb
   ```

## Analysis Workflow

1. **Data Preprocessing**: Clean and format traffic and air quality data
2. **Temporal Analysis**: Examine patterns throughout the day (morning, afternoon, evening)
3. **Spatial Analysis**: Analyze air quality variations across different drone flight paths
4. **Correlation Analysis**: Investigate relationships between traffic metrics and air quality measurements
5. **Visualization**: Create plots and maps to illustrate findings

## Key Findings

_To be updated with analysis results_

## Author

Master's Thesis Project

## License

_To be specified_

## Contact

For questions or collaboration inquiries, please open an issue in this repository.
