# Demand Forecasting Model

This repository contains an analytical project that focuses on customer demographics, transactional data, and product information in the retail domain. It integrates data preprocessing, forecasting, and web-based visualization using Python, making it a comprehensive solution for retail data analysis and predictive modeling.

## Project Structure

- *app.py*: The main Python script that powers the web application. It processes customer and transactional data, applies machine learning models for forecasting, and visualizes insights.
  
- *CustomerDemographics.csv*: A dataset containing various demographic attributes of customers, such as age, gender, and location. This data is essential for understanding customer segmentation and behavior.

- *Transactional_data_retail_01.csv & Transactional_data_retail_02.csv*: Retail transaction records containing purchase information. These datasets are used for sales analysis, trend forecasting, and customer behavior analysis.

- *ProductInfo.csv*: This file contains details about products, such as product names, categories, and prices. It helps analyze product performance and preferences among customers.

- *forecasted_data.csv*: Contains forecasted results derived from historical data. These predictions can be used for strategic decision-making in inventory management and customer targeting.

- *templates*: A folder containing HTML templates used by the Flask or Streamlit app to create the front-end for displaying visualizations and predictions.

## Features

1. *Data Cleaning & Preprocessing*: The app.py script includes functions for cleaning raw customer and transactional data, removing noise, and preparing datasets for analysis.
  
2. *Predictive Modeling*: The project uses machine learning models to generate forecasts based on transactional data. The predictions can help businesses make informed decisions about inventory, marketing, and customer engagement.

3. *Interactive Web Application*: Using Streamlit or Flask, the project provides an intuitive web-based interface to allow users to upload their data, view predictions, and explore various insights.

4. *Visualization*: The app visualizes key insights, such as customer trends, product preferences, and sales forecasts. This helps users interact with the data and extract valuable business intelligence.

## Requirements

- Python 3.x
- Libraries: 
  - pandas
  - numpy
  - scikit-learn
  - Flask
  - nltk
  
Install the required libraries using:

bash
pip install -r requirements.txt


## How to Run

1. Clone this repository:
   bash
   git clone https://github.com/yourusername/soothsayer-analytics-assignment.git
   cd soothsayer-analytics-assignment
   

2. Install the dependencies:
   bash
   pip install -r requirements.txt
   

3. Run the application:
   bash
   python app.py
   

4. Open the web app in your browser to interact with the insights and predictions.

## Data Sources

- *CustomerDemographics.csv*: Contains customer demographic information.
- *Transactional_data_retail_01.csv & Transactional_data_retail_02.csv*: Contains records of retail transactions.
- *ProductInfo.csv*: Contains information about products sold.
- *forecasted_data.csv*: Predicted data based on historical trends.
