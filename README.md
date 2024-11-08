# NYC Subway Station Activity Clustering Analysis

This repository contains code and analysis for clustering NYC subway station activity levels based on entry and exit counts. Using data from the [MTA Subway Turnstile Usage Data 2022](https://data.ny.gov/Transportation/MTA-Subway-Turnstile-Usage-Data-2022/k7j9-jnct/about_data), we categorize stations by their usage patterns over a single day. The goal is to help transit authorities optimize resource allocation by identifying low, moderate, and high-activity stations.

## Contents

- **Data Cleaning**: Steps to preprocess and clean the dataset, including encoding categorical variables and removing irrelevant columns.
- **Clustering Analysis**: Implementation of KMeans clustering to categorize station activity based on entries, exits, time of day, and station location.
- **Visualization**: Plots showing cluster distributions, including:
  - Overall station activity (entries vs. exits)
  - Hourly breakdown of activity per station
- **Results**: Interpretation of clusters and insights for transit authorities to optimize staffing, maintenance, and passenger flow based on station activity.

## Key Files

- `clustering_analysis.py`: Data cleaning and preparation scripts and code for KMeans clustering and Elbow Method to determine optimal `k`.
- `README.md`: Project overview and instructions.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`

## Usage

1. Clone the repository.
3. Execute `clustering_analysis.py` to perform clustering on the data.


## Data Source

Data is sourced from the [New York State Open Data Portal - MTA Subway Turnstile Usage Data 2022](https://data.ny.gov/Transportation/MTA-Subway-Turnstile-Usage-Data-2022/k7j9-jnct/about_data).
