# A Comparative Study of Public Bike Sharing Systems in Dublin and Boston

This project focuses on the comparative analysis of two public bike-sharing systems: DublinBikes in Dublin, Ireland, and BlueBikes in Boston, USA. The aim is to explore the usage patterns, user satisfaction, and predict future bike usage using machine learning models. The project was conducted using the CRISP-DM framework, and it involves extensive data cleaning, visualization, statistical analysis, and sentiment analysis.

## Project Overview

Objective: To compare bike-sharing systems in Dublin and Boston, analyze trends, forecast bike service usage, and perform sentiment analysis based on public reviews from Reddit.

## Key Features:

- Data cleaning and preprocessing of 24 datasets (12 for each city for the year 2022).
- Exploratory data analysis (EDA) of bike trips, including geographical distribution, most/least utilized stations, and trip patterns by day and month.
- Statistical analysis to determine trends and patterns in both systems.
- Machine learning models (XGBoost and Random Forest) to predict bike usage trends.
- Sentiment analysis of user reviews sourced from Reddit, using NLP techniques.

## Tools and Technologies

- Programming Languages: Python
- Libraries:

    Data processing: Pandas, Numpy

    Visualization: Matplotlib, Seaborn, Plotly

    Machine Learning: Scikit-learn, XGBoost, Random Forest

    Sentiment Analysis: NLTK, TextBlob, PRAW

    API handling: PRAW (Python Reddit API Wrapper)

    Framework: CRISP-DM (Cross Industry Standard Process for Data Mining)

## Data Sources

- DublinBikes: data.gov.ie
- BlueBikes Boston: bluebikes.com
- Reddit reviews: Scraped using PRAW API

## CRISP-DM Framework

- Business Understanding: Analyze public bike-sharing usage in two cities.
- Data Understanding: Collect public data from official sources and Reddit.
- Data Preparation: Clean and preprocess datasets, handle missing values, and engineer features.
- Modeling: Build and fine-tune models to predict bike usage trends.
- Evaluation: Validate model performance with metrics like R² and Mean Squared Error.
- Deployment: This repository contains the code and documentation for all steps in the analysis.

## Project Structure

- data/: Contains the raw datasets used in this project.
- notebooks/: Jupyter notebooks with data processing, visualization, and model implementation.
- README.md: Project documentation.


## Key Results

- EDA: Insights on geographical distribution, usage patterns, and peak usage periods.
- Statistics: Significant differences in bike usage between Dublin and Boston, especially in terms of variability and peak periods.
- Machine Learning: XGBoost performed better than Random Forest in predicting monthly bike trips.
- Sentiment Analysis: Sentiment analysis revealed that BlueBikes Boston had more positive feedback compared to DublinBikes.


## Usage

- Open the Jupyter notebooks  to explore the data cleaning, EDA, and machine learning models.
- Use the Python scripts to replicate the analysis on other datasets.

## License

This project is licensed under the Creative Commons Attribution 4.0 License. Data sources follow their respective licenses (CC BY 4.0 for DublinBikes and the BlueBikes data license agreement).

## Acknowledgments

This project was developed as part of a comparative study between two urban bike-sharing systems. Special thanks to the creators of the datasets and the open-source community for providing valuable resources.
