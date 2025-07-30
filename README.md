# Weather Prediction: Will It Rain Tomorrow?

This project aims to predict whether it will rain tomorrow using historical weather data from Australia.

## Dataset
The dataset contains 145,460 daily observations of 23 features from weather stations across Australia. Key features include temperature, humidity, pressure, wind direction/speed, and cloud cover.

Download the dataset from [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package) and place it in `data/raw/`.

## Project Structure
- `notebooks/`: Jupyter notebooks for EDA, feature engineering, modeling, and evaluation
- `src/`: Python scripts for data processing and modeling
- `data/`: Contains raw and processed data

## Setup
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Download the dataset and place in `data/raw/`

## Approach
1. Exploratory Data Analysis
2. Feature Engineering
3. Model Training (Time Series Aware)
4. Model Evaluation

## Time Series Considerations
We'll use time-based splits to avoid data leakage, with the first 80% of dates for training and the last 20% for testing.
