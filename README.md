# Bike Sharing Demand Prediction

This project aims to build a multiple linear regression model to predict the demand for shared bikes. The model helps understand the factors affecting bike demand and provides insights for BoomBikes, a US-based bike-sharing provider, to strategize and increase revenue, especially in the context of the post-COVID-19 scenario.

## Project Overview

BoomBikes has experienced a significant dip in revenue due to the COVID-19 pandemic. To recover and plan effectively for the future, they need to understand the factors influencing bike-sharing demand. This project involves:

1. **Data Preparation and Exploration**: Cleaning and transforming the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing data to uncover patterns and relationships.
3. **Model Building**: Creating a multiple linear regression model to predict bike demand.
4. **Model Evaluation**: Assessing the model's performance and analyzing residuals.

## Dataset

The dataset contains daily bike demand information with various features such as:

- **Season**: Categorical (spring, summer, fall, winter)
- **Weather Situation**: Categorical (Clear, Mist, Light Snow, Heavy Rain)
- **Temperature**: Continuous
- **Humidity**: Continuous
- **Windspeed**: Continuous
- **Holiday**: Binary
- **Working Day**: Binary
- **Year**: Binary (0: 2018, 1: 2019)
- **Month**: Categorical
- **Weekday**: Categorical
- **Casual Users**: Continuous (Number of casual users)
- **Registered Users**: Continuous (Number of registered users)
- **Total Count (`cnt`)**: Continuous (Total number of bike rentals)
