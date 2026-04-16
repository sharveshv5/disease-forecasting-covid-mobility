###### **Disease Forecasting using COVID-19 and Mobility Data**



**Overview**

This project analyzes and forecasts COVID-19 case trends in India by integrating epidemiological data with human mobility patterns.



**Datasets**

* COVID-19 Time-Series Data (Johns Hopkins University)
* Google Community Mobility Reports



**Approach**

* Data Preprocessing and Transformation
* Feature Engineering (Lag Features, Rolling Mean, Seasonality)
* Random Forest Model for Forecasting
* Baseline Comparison for Evaluation



**Results**

The Model captures Overall Trends but performs comparably to a Naive Baseline, highlighting the strong Autoregressive nature of COVID-19 Case Dynamics.



**How to Run**

1\. Install Dependencies: pip install -r requirements.txt

2\. Open the Notebook: notebook/disease\_forecasting.ipynb



**Project Structure**

* data/raw → datasets
* notebook → main analysis
* requirements.txt → dependencies



**Key Insight**

COVID-19 Trends are highly dependent on Past values, and Mobility data has limited predictive impact at the National level.

**Data Note**

The mobility dataset is large (>1GB) and is not included due to GitHub size limits.

Download from: https://www.google.com/covid19/mobility/

Place it in: data/raw/mobility.csv



