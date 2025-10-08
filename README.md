# Mass-Shooting-Prediction-Using-Time-Series-Analysis
This project uses time-series forecasting to analyze and predict trends in mass shooting incidents in the United States, inspired by the research paper "Mass Shooting Prediction Using Time Series." It leverages the Prophet model to identify patterns, seasonality, and long-term trends in historical data.
# Features
- Data Processing: Loads and preprocesses a historical dataset of mass shootings.

- Time-Series Modeling: Utilizes Prophet to capture yearly and weekly seasonality.

- Forecasting: Predicts the trend of incidents for the next 365 days.

- Visualization: Generates plots of the forecast and its trend/seasonality components.

# Dataset
This project uses the "Mass Shootings in the US (1966-2017)" dataset from Kaggle.

Please download the dataset from the link below and place Mass-Shootings-Dataset-Ver-5.csv in a data/ directory:
https://www.kaggle.com/datasets/zusmani/us-mass-shootings-last-50-years

# How to Run
1. Clone the repository and cd into it.

2. Create a data directory and place the dataset CSV inside.

3. Install dependencies: pip install -r requirements.txt

4. Run the prediction script: python predict.py

5. Check the output: The script will generate forecast_plot.png and forecast_components.png.
