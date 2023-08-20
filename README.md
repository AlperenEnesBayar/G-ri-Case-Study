# Wind Energy Power Production Prediction

This repository contains a project focused on building a model for predicting wind energy power production. The project aims to forecast the amount of power that a wind plant will generate based on factors such as air density and wind speed.

## Project Overview

In this project, we develop a predictive model for wind energy power production, enabling efficient planning and decision-making in the wind energy field. The project consists of the following key components:

- Data Exploration and Preprocessing: We analyze and preprocess the provided data sets, including air density, wind speed, and power production records. Missing data is handled, and features are normalized for optimal model performance.

- Feature Engineering: Additional features are derived from the timestamp, including hour of day, day of week, and month. These features enhance the model's ability to capture temporal patterns.

- Model Selection and Training: We implement a Recurrent Neural Network (RNN) model to predict power production. The RNN is chosen due to its ability to capture sequential dependencies in time-series data. The model is trained and validated using appropriate data splits.

- Hyperparameter Tuning and Model Evaluation: Hyperparameters of the RNN model are fine-tuned to optimize its performance. Model evaluation is based on the Mean Squared Error (MSE) metric, measuring prediction accuracy.

- Forecast: The trained RNN model is utilized to make power production forecasts. The accuracy of the forecasts is evaluated based on the model's performance.

## Getting Started

To replicate or further develop this project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/wind-energy-prediction.git
cd wind-energy-prediction
```
2. Install required dependencies:
```bash
pip install -r requirements.txt
```
3. Run the project:
Modify the data loading, preprocessing, and modeling sections as needed for your data.

Directory Structure
The project directory is organized as follows:
```css
├── GurisCaseStudy.ipynb
├── README.md
├── requirements.txt
├── air_properties_data.xlsx
├── power_data.xlsx
```
