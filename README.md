# Garmin Fitness Analytics

A personal data analytics project exploring Garmin activity data with **Tableau**.

The goal of this project was to practice data cleaning, calculated fields, interactive dashboards, data visualization, and exploratory analysis using real-world fitness data.

## Dataset

The dataset contains approximately **1,300 Garmin activities recorded between 2024 and 2026**.

The main activity types include:

* Walking
* Strength Training
* Indoor Rowing
* Cycling
* Running

The original Garmin export is not included in this repository because it contains personal activity and location information.

## Data Preparation

Several fields required cleaning or transformation before they could be used effectively in Tableau.

Examples include:

* Converting activity duration into training minutes
* Handling missing values
* Converting distance and heart-rate fields into numeric values
* Cleaning step counts
* Creating Year, Month, Weekday and Hour dimensions
* Extracting activity locations for geographic analysis

## Dashboard

![Garmin Fitness Dashboard](Dashboard Garmin Acitivites.png)

The main dashboard provides an overview of my training activity and includes:

* Total activities
* Total training hours
* Total calories
* Total distance
* Monthly activity trend
* Activity type breakdown
* Training consistency heatmap
* Interactive year and activity-type filters

The dashboard also uses Tableau dashboard actions, allowing individual activity types to be selected directly from the visualizations.


## Tools

* Tableau
* Garmin activity data
* Git
* GitHub

## Skills Demonstrated

* Data cleaning
* Calculated fields
* Time-series analysis
* KPI design
* Heatmaps
* Scatter plots
* Dashboard design
* Interactive filters
* Dashboard actions
* Exploratory data analysis
