# Mortality Forecast in Madrid Using Time Series and Climate Variables

This repository contains materials for a project on forecasting daily mortality in Madrid using time series data enriched with climate variables such as temperature. The goal is to build predictive models to estimate future mortality based on historical data and exogenous climate variables.

## Repository Structure

- `madrid_mortality_forecast_with_climate_exogenous_variables.ipynb`: The main Jupyter notebook containing the code for time series analysis and forecasting.

## Project Description

### Objective

The project aims to analyze daily mortality trends in Madrid, incorporating exogenous climate variables (such as temperature) to enhance the predictive model's accuracy.

### Dataset

The dataset consists of daily mortality records from Madrid starting from 2015, along with climate data (average, minimum, and maximum temperature).

### Key Components

- **Data Loading**: Importing mortality and climate data.
- **Data Preprocessing**: Handling missing values, setting date indices, and preparing data for time series analysis.
- **Modeling**: Using autoregressive models to forecast mortality, incorporating exogenous variables like temperature.
- **Evaluation**: Measuring prediction performance using MAE and other relevant metrics.

## Requirements

- `Python 3.x`
- `pandas`
- `numpy`
- `matplotlib`
- `skforecast`
- `scikit-learn`

Install the required dependencies using:

```bash
pip install pandas numpy matplotlib scikit-learn skforecast
```
## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```
2.	Open `madrid_mortality_forecast_with_climate_exogenous_variables.ipynb` in Jupyter Notebook or Jupyter Lab.
3.	Follow the instructions in the notebook to run the analysis and forecast future mortality rates.

## Acknowledgments

This project was developed by **Felipe Guzmán**, **Álvaro Alcalde**, and **Pablo Díaz-Masa** for the **Machine Learning in Time Series and Data Streams** course.
