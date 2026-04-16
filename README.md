# Disease Forecasting using COVID-19 and Mobility Data

## Overview
This project analyzes and forecasts COVID-19 case trends in India by integrating epidemiological data with human mobility patterns.

## Datasets
- COVID-19 Time-Series Data (Johns Hopkins University)
- Google Community Mobility Reports

## Approach
- Data preprocessing and transformation  
- Feature engineering (lag features, rolling mean, seasonality)  
- Supervised forecasting using lag-based features  
- Random Forest model with baseline comparison  

## Results
The model captures overall trends but underperforms compared to a naive baseline, highlighting the strong autoregressive nature of COVID-19 case dynamics.

## How to Run
1. Install dependencies : `pip install -r requirements.txt`
2. Open the notebook : `notebooks/disease_forecasting.ipynb`

## Project Structure
- `data/raw` → datasets  
- `notebook` → main analysis  
- `requirements.txt` → dependencies  

## Key Insight
COVID-19 trends are highly dependent on past values, and mobility data has limited predictive impact at the national level.

## Data Note
The mobility dataset is large (>1GB) and is not included due to GitHub size limits.

Download from:  
https://www.google.com/covid19/mobility/

Place it in:  
`data/raw/mobility.csv`
