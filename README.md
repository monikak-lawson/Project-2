# Project-2
This project involved creating an interactive dashboard in Power BI using Python for forecasting.

# Project: New Zealand Dollar (NZD) Exchange Rate Prediction

This project was undertaken as part of a course and focuses on the historical analysis of exchange rate and GDP developments, with the primary goal of predicting the future trend of the New Zealand Dollar (NZD) exchange rate.

## Overview

The project analyzes historical exchange rate and GDP data, specifically aiming to predict the NZD exchange rate for the next two years. Machine learning methods implemented in Python were used for this purpose. Power BI was utilized for data visualization and further analysis.

## Data Sources

The data for this project comes from the following sources:

* **Czech National Bank (ČNB)**: Historical exchange rate data.
* **Reserve Bank of New Zealand**: Historical GDP data for New Zealand.

## Technologies

The project utilizes the following technologies:

* **Python**: Programming language for data analysis, implementation of machine learning models, and data manipulation.
* **Power BI**: Tool for data visualization and creating interactive dashboards.

## Methodology

Two different machine learning models were implemented in Python to predict the NZD exchange rate:

1.  **Linear Regression with Seasonal Effect and Random Noise**:
    * This model utilizes New Zealand's GDP data.
    * It focuses on considering the impact of economic crises in New Zealand, specifically in the years 1998, 2009, 2020, 2022, and 2024.
    * The model attempts to capture the underlying trend and seasonal fluctuations in GDP data and their potential impact on the NZD exchange rate.

2.  **KNeighborsRegressor**:
    * This model uses historical NZD exchange rate data.
    * The data was split into training and testing sets.
    * Based on the similarity to historical data, the model generates a prediction for the future exchange rate trend.

Undertaking this project as part of the course provided me with valuable experience and knowledge in several areas:

* **Practical Application of Machine Learning**: I learned how to apply different machine learning models (linear regression and k-nearest neighbors) to real-world economic data.
* **Working with Time Series Data**: I gained a deeper understanding of the specifics of time series analysis and prediction, including considering seasonality and external influences (such as economic crises).
* **Data Acquisition and Cleaning**: I practiced the process of acquiring data from various sources (ČNB, Reserve Bank of New Zealand) and preparing it for further analysis.
* **Utilizing Power BI**: I developed skills in data visualization and creating interactive reports in Power BI, which allowed me to better present the analysis results.
* **Understanding Economic Context**: The project deepened my understanding of the relationships between macroeconomic indicators (GDP) and exchange rates.
* **Solving a Real-World Problem**: I had the opportunity to work on a practical problem of financial market prediction, which gave me a more realistic perspective on the possibilities and limitations of data analysis and machine learning.
* **Improving Python Programming Skills**: During the implementation of the models, I strengthened and expanded my Python programming skills and my ability to work with relevant libraries.
