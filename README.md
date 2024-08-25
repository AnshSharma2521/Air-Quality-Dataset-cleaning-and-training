# Air Quality Dataset cleaning and training
# Air Quality Dataset Analysis

This repository contains the analysis and modeling of an air quality dataset. The dataset has been cleaned and preprocessed, and then two machine learning models—Decision Tree and Random Forest—were trained to predict air quality with an accuracy of 94% and 96%, respectively.

## Dataset Description

The dataset used in this project consists of daily air quality measurements across various cities. The data includes the following features:

- **Date**: The date of the measurement.
- **City**: The city where the measurement was taken.
- **PM2.5**: Concentration of particulate matter with a diameter of less than 2.5 micrometers.
- **PM10**: Concentration of particulate matter with a diameter of less than 10 micrometers.
- **NO**: Concentration of Nitric Oxide.
- **NO2**: Concentration of Nitrogen Dioxide.
- **NOx**: Concentration of Nitrogen Oxides.
- **NH3**: Concentration of Ammonia.
- **CO**: Concentration of Carbon Monoxide.
- **SO2**: Concentration of Sulfur Dioxide.
- **O3**: Concentration of Ozone.
- **Benzene**: Concentration of Benzene.
- **Toluene**: Concentration of Toluene.
- **Xylene**: Concentration of Xylene.
- **AQI**: Air Quality Index, a measure of how polluted the air is.

## Preprocessing Steps

1. **Handling Missing Values**: Removed all rows with null values to ensure a clean dataset.
2. **Outlier Removal**: Detected and removed outliers to avoid skewed results.
3. **Scaling**: Applied scaling to the features to normalize the data, ensuring that all features contribute equally to the model.
4. **Encoding**: Encoded categorical variables such as the 'City' column to numerical values for model compatibility.

## Modeling

Two machine learning models were trained on the cleaned dataset:

1. **Decision Tree**: A model that makes decisions based on the features, achieving an accuracy of 94%.
2. **Random Forest**: An ensemble model that builds multiple decision trees and averages their predictions, achieving an accuracy of 96%.

## How to Use

To run the analysis and train the models, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/YourUsername/air-quality-analysis.git
   cd air-quality-analysis
## **Author**
Ansh Sharma
