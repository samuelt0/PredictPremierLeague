# Overview

This project aims to predict the outcomes of Premier League football matches by leveraging historical data and machine learning techniques. The workflow involves scraping data, cleaning it, and using predictive models to forecast match results.

## Data Collection and Preparation

Data Source: Team and game data was scraped from fbref.com.
Data Cleaning: The raw data was cleaned using Python's pandas library.
Exported Data: Cleaned data was saved as a CSV file for further analysis and modeling.

## Predictive Modeling

Models: The Random Forest and Multilayer Perceptron (MLP) models from SkLearn were used.
Metrics: Custom metrics were calculated using rolling averages to enhance prediction accuracy.
