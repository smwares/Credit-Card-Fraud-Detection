# 💳Credit Card Fraud Detection

[![Made with Google Colab](https://img.shields.io/badge/Made%20with-Google%20Colab-orange?style=for-the-badge)](https://colab.research.google.com/)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge)](https://www.python.org/)
[![Made with Tableau](https://img.shields.io/badge/Made%20with-Tableau-green?style=for-the-badge)](https://creativecommons.org/publicdomain/zero/1.0/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge)](https://github.com/fursuf1/Credit-Card-Fraud-Detection)
[![Visual Studio Code](https://img.shields.io/badge/Editor-Visual%20Studio%20Code-blue?style=for-the-badge)](https://code.visualstudio.com/)
[![git](https://badgen.net/badge/icon/git?icon=git&label)](https://git-scm.com)
[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)

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

- This dataset is comprehensive log of simulated credit card transactions with over 1.85 million entries, providing a realistic and diverse environment (and thus valuable) for our investigation.
- The transactions span from January 1st, 2019 to December 31st, 2020 and encompasses both legitimate and fraudulent transactions.
- The dataset features transactions by 1,000 customers in over 900 cities all across the US engaging with around 700 distinct merchants.
- The purchases are categorized in 14 different categories and the amount spent ranges from as little as $1 to as much as $29,000.
- Only 9651 of the 1.85 million transactions (0.52%) were fraudulent.

### 🔑Key Dataset Features
The dataset includes essential features for analysis:

- **Timestamp (Time)**: Each transaction is timestamped, enabling time-based pattern analysis.
- **Merchant Details**: Name of merchant and geolocations (i.e. latitude & longitude).
- **Transaction Categories**: Category of the type of product purchased.
- **Transaction Amount**: How much was spent for each transaction.
- **Credit Card Holder Information**: Names, gender, dates of birth, addresses, CC numbers.
- **Fraud Indicator (is_fraud)**: A binary flag (1 for fraudulent transactions, 0 for legitimate).

### 📂 Data Source
This dataset was generated using the Sparkov Data Generation tool, available on GitHub, developed by Brandon Harris. This tool allowed us to simulate transactions covering the period from January 1st, 2019, to December 31st, 2020. The generated data files were meticulously combined and transformed into a standardized format.

### 🧹 Data Quality
The dataset is meticulously prepared, with no missing values, ensuring the integrity of our analysis. Additionally, any duplicated entries have been removed to maintain data accuracy.
This data preparation provides a reliable foundation for our analysis of fraudulent activities within credit card transactions.


## 🏠 Dataset Link

[Credit Card Fraud Dataset on Kaggle](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

## ❓Questions for Analysis

### 1️⃣ **Question**: What is the distribution of transaction amounts in fraudulent vs. legitimate transactions?
   - **Method**: Analyze the transaction amounts and create visualizations to compare distributions between fraudulent and legitimate transactions.

### 2️⃣ **Question**: Are there specific time patterns when fraudulent transactions are more likely to occur?
   - **Method**: Analyze the timestamp data to identify any time patterns associated with fraudulent transactions.

### 3️⃣ **Question**: Can you identify any geographical patterns in fraud occurrences based on transaction attributes?
   - **Method**: Investigate whether location-related attributes (if available) exhibit patterns in fraud occurrences.

### 4️⃣ **Question**: Do certain features, such as location or gender, correlate with fraud?
   - **Method**: Perform correlation analysis and visualize correlations using a heatmap.

### 5️⃣ **Question**: What is the distribution of transaction amounts, and are there any unusual patterns?
   - **Method**: Create a histogram or box plot to visualize the distribution of transaction amounts.

### 6️⃣ **Question**: Is there a temporal pattern to fraudulent transactions (e.g., certain days of the week or times of day)?
   - **Method**: Use a time series line chart to visualize the number of fraudulent transactions over time.

### 7️⃣ **Question**: Are there specific merchant categories more prone to fraudulent activity?
   - **Method**: Develop a bar chart showing the number of fraudulent transactions by merchant category.

These questions, along with the specified methods, will help uncover valuable insights into fraud detection through data analysis, modeling, and forecasting.

## 📊Conclusion:

Fraudulent transactions displayed a noticeable trend, primarily occurring during specific periods, typically a few hours before and after midnight.
These fraudulent transactions were characterized by notably lower spending amounts.
Many other transaction patterns resembled those of legitimate transactions.
However, due to the dataset's scarcity of fraudulent instances and the intricate nature of the patterns, employing advanced modeling techniques like random forest is imperative for effective classification.

## 📓 Authors

- [@smwares](https://github.com/smwares)

- [@fursuf1](https://github.com/fursuf1)

## 🚀 About Me

**🌟Talking about Personal Stuffs:**

- 👨‍🏛 I am currently a student of **LHL**.
- 🌱 I'm currently learning **Data Sciences**. 
- 💬 If you have any questions, **just ask me**.

## 🔍 References
[CSV FILE](https://www.mediafire.com/file/4olkuu3ehwoihgl/fraud_cleaned.csv/file)




