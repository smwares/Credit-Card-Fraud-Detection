# 💳Credit Card Fraud Detection

[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge)](https://jupyter.org/)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge)](https://www.python.org/)
[![Made with Tableau](https://img.shields.io/badge/Made%20with-Tableau-green?style=for-the-badge)](https://creativecommons.org/publicdomain/zero/1.0/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge)](https://github.com/fursuf1/Credit-Card-Fraud-Detection)
[![Visual Studio Code](https://img.shields.io/badge/Editor-Visual%20Studio%20Code-blue?style=for-the-badge)](https://code.visualstudio.com/)

**Table of Contents**
- [💳Credit Card Fraud Detection](#credit-card-fraud-detection)
- [📊🚧Project Overview](#project-overview)
- [📈About the Dataset](#about-the-dataset)
  - [📝 Description](#description)
  - [🔑Key Dataset Features](#key-dataset-features)
  - [📂 Data Source](#data-source)
  - [🧹 Data Quality](#data-quality)
- [🏠 Dataset Link](#dataset-link)
- [❓Questions for Analysis](#questions-for-analysis)
- [📊Results](#results)
- [📓 Authors](#authors)
- [🚀 About Me](#about-me)
- [🌟References](#references)


## 📊🚧Project Overview

In this analysis, we delve into the Credit Card Transactions Fraud Detection Dataset. Our primary goal is to conduct exploratory data analysis (EDA) to identify essential features associated with fraudulent activities. Subsequently, we will employ forecasting techniques using various charts and graphs to gain insights from the data and predict trends. Additionally, we will evaluate the effectiveness of our forecasting in detecting fraud. To ensure a seamless presentation of our insights, we will construct an interactive dashboard, providing a comprehensive view of credit card transaction fraud detection.

## 📈About the Dataset

### 📝 Description
This dataset provides a comprehensive log of credit card transactions spanning from January 1st, 2019, to December 31st, 2020. It encompasses both legitimate and fraudulent transactions, offering a valuable resource for fraud detection analysis. The dataset features transactions from 1,000 customers engaging with around 800 distinct merchants, providing a realistic and diverse environment for our investigation.

### 🔑Key Dataset Features
The dataset includes essential features for analysis:

- **Timestamp (Time)**: Each transaction is timestamped, enabling time-based pattern analysis.
- **Merchant Details**: Comprehensive information about the involved merchants, shedding light on transaction origins.
- **Transaction Categories**: Transactions are categorized, allowing insights into the nature of purchases.
- **Transaction Amount**: The monetary value of each transaction is provided, a crucial element for analysis.
- **Credit Card Holder Information**: Personal data about credit card holders, encompassing names, genders, locations, and birthdays.
- **Fraud Indicator (is_fraud)**: A binary flag (1 for fraudulent transactions, 0 for legitimate ones) guides our efforts to identify fraudulent activities.

### 📂 Data Source
This dataset was generated using the Sparkov Data Generation tool, available on GitHub, developed by Brandon Harris. This tool allowed us to simulate transactions covering the period from January 1st, 2019, to December 31st, 2020. The generated data files were meticulously combined and transformed into a standardized format.

### 🧹 Data Quality
The dataset is meticulously prepared, with no missing values, ensuring the integrity of our analysis. Additionally, any duplicated entries have been removed to maintain data accuracy.
This data preparation provides a reliable foundation for our analysis of fraudulent activities within credit card transactions.





## 🏠 Dataset Link

[Credit Card Fraud Dataset on Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)

## ❓Questions for Analysis

### 1️⃣ **Question**: What is the distribution of transaction amounts in fraudulent vs. legitimate transactions?
   - **Method**: Analyze the transaction amounts and create visualizations to compare distributions between fraudulent and legitimate transactions.

### 2️⃣ **Question**: Are there specific time patterns when fraudulent transactions are more likely to occur?
   - **Method**: Analyze the timestamp data to identify any time patterns associated with fraudulent transactions.

### 3️⃣ **Question**: Can you identify any geographical patterns in fraud occurrences based on transaction attributes?
   - **Method**: Investigate whether location-related attributes (if available) exhibit patterns in fraud occurrences.

### 4️⃣ **Question**: Are there any common trends or characteristics shared among fraudulent transactions in this dataset?
   - **Method**: Investigate commonalities among fraudulent transactions to identify any recurring trends or characteristics.

### 5️⃣ **Question**: Do certain features, such as location or gender, correlate with fraud?
   - **Method**: Perform correlation analysis and visualize correlations using a heatmap.

### 6️⃣ **Question**: What is the distribution of transaction amounts, and are there any unusual patterns?
   - **Method**: Create a histogram or box plot to visualize the distribution of transaction amounts.

### 7️⃣ **Question**: Is there a temporal pattern to fraudulent transactions (e.g., certain days of the week or times of day)?
   - **Method**: Use a time series line chart to visualize the number of fraudulent transactions over time.

### 8️⃣ **Question**: Are there specific merchant categories more prone to fraudulent activity?
   - **Method**: Develop a bar chart showing the number of fraudulent transactions by merchant category.

### 9️⃣ **Question**: Can we forecast the potential increase in fraud based on historical data trends?
   - **Method**: Use time series forecasting techniques, such as ARIMA or Prophet, to predict future fraud trends. Display these forecasts in the dashboard.

These questions, along with the specified methods, will help uncover valuable insights into fraud detection through data analysis, modeling, and forecasting.

## 📊Results

## 📓 Authors

## 🚀 About Me

## 🌟References




