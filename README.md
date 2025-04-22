# Crime Analysis in India (2001–2014)

**A data visualization and analytics project developed for UTA Datathon 2025.**  
This project explores trends in crimes reported under the Indian Penal Code (IPC) across Indian districts from 2001 to 2014. It leverages geospatial data, statistical modeling, and interactive dashboards to extract insights and support public policy discussions.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Project Files](#project-files)
- [How to Run](#how-to-run)
- [Dataset Source](#dataset-source)
- [Team & Acknowledgements](#team--acknowledgements)

## Overview

Crime patterns across India have shown notable regional, urban-rural, and temporal variations. Using official government data, this project analyzes:

- Which districts report the highest crime rates?
- How has crime evolved between 2001 and 2014?
- Are there notable differences between urban and rural crime?
- Can we model or predict future crime trends?

## Key Features

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| Time-Series Trends         | Analyze how crime evolved over the years in different regions.              |
| Geospatial Heatmaps        | Visualize crime intensity by district using Indian shapefiles.             |
| Urban vs Rural Comparison | Explore crime patterns based on area classification.                       |
| Top Offender Districts     | List of districts with the most crime over the years.                      |
| Predictive Modeling        | Linear regression for simple crime trend forecasting.                      |
| Streamlit Dashboard        | Interactive UI for quick insights and filtering by year/district/type.     |

## Tech Stack

| Category       | Tools Used                                                                 |
|----------------|----------------------------------------------------------------------------|
| Programming    | Python                                                                     |
| Libraries      | Pandas, NumPy, Seaborn, Matplotlib, Plotly, GeoPandas, Scikit-learn        |
| Visualization  | Streamlit, Folium, Plotly                                                  |
| Data Format    | CSV (Crime Data), GeoJSON (District Boundaries)                            |
| Platform       | Local or Streamlit Cloud                                                   |

## Project Files

| File Name                                  | Description                                                 |
|-------------------------------------------|-------------------------------------------------------------|
| `EDA_Patrol.ipynb`                        | Jupyter Notebook for EDA and modeling                       |
| `EDA Patrol - Solution.pdf`               | Summary document with charts and observations               |
| `Districtwise_Crime_of_India_2001_to_2014 - Sheet1.csv` | Raw dataset used for analysis               |
| `india_district.zip`                      | District-level shapefile for mapping                        |
| `app.py` *(optional)*                     | Streamlit app for interactive dashboard                     |

---

## How to Run

> Ensure Python ≥ 3.8 is installed.

**Clone the repository**:
   ```bash
   git clone https://github.com/hariharan-uta/Crime_Analysis_India.git
   cd Crime_Analysis_India
