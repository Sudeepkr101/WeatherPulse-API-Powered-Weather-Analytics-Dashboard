# WeatherPulse — API-Powered Weather Analytics Dashboard

## Project Overview

This project uses a free weather API as an external weather-data source and Microsoft Power BI to analyze and visualize current weather, daily forecasts, hourly forecasts, and air-quality information. It provides an interactive and insightful look into real-time and predicted meteorological data.

## Features

* Current weather monitoring
* Daily forecast analysis
* Hourly forecast analysis
* Temperature analysis
* Rain probability and precipitation
* Wind and atmospheric conditions
* Air-quality information
* Location-based analysis
* Interactive Power BI dashboard

## Tech Stack

* Weather API
* Microsoft Power BI
* Power Query
* Microsoft Excel
* API data / structured response

## Data Workflow

Weather API
↓
Data Collection
↓
Data Transformation
↓
Excel Datasets
↓
Power BI Data Model
↓
Interactive Dashboard

## Project Files

* **WeatherAPI Project.pbix**: The core Microsoft Power BI file containing the data model, relationships, and interactive dashboard visuals.
* **Current.xlsx**: Contains extracted datasets for real-time current weather conditions.
* **Forcast_Day.xlsx**: Holds daily forecast data to analyze upcoming weather trends over several days.
* **Forcast_Hour.xlsx**: Stores granular hourly forecast data to monitor short-term weather fluctuations.
* **MasterReport.xlsx**: A consolidated dataset or summary report mapping out overall metrics.
* **WeatherAPI_Project_Documentation.docx**: Comprehensive documentation detailing project setup, methodology, and the steps taken to process and visualize the data.

## API Security

API credentials should never be committed to a public repository. Any API key used during the development of this dashboard must be protected, stored securely, and kept out of version control. 

## Future Improvements

* Automated API refresh
* Historical weather analysis
* Weather alerts
* Forecast vs actual analysis
* Power BI Service deployment
* Secure API credential management
