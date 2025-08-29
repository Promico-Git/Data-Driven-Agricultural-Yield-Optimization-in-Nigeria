# Data-Driven Agricultural Yield Optimization in Nigeria

This project performs an in-depth analysis of an agricultural dataset to provide data-driven recommendations for the most productive locations to grow various crops. The goal is to maximize annual yield by considering a range of environmental and agricultural factors.

## Project Workflow

* **Data Cleaning & Preprocessing:** The raw dataset was thoroughly cleaned by correcting swapped columns, fixing typos in crop types (e.g., "Cassaval" to "Cassava"), and imputing missing temperature values using location-specific means.

* **Exploratory Data Analysis (EDA):** A detailed EDA was conducted to understand data distributions, identify outliers using boxplots, and test for normality using histograms and the Shapiro-Wilk test.

* **Feature Engineering (KPIs):** Several Key Performance Indicators (KPIs) were developed to measure agricultural performance, including:
    * Yield per Unit Area
    * Water Use Efficiency
    * Soil Fertility Yield Ratio
    * Pollution Impact on Yield

* **Performance Analysis & Visualization:** The KPIs were normalized using a `MinMaxScaler` and aggregated into a 'Total KPI' score to rank the best locations for each crop type. The final recommendations are presented in a summary bar chart.

## Key Findings

The analysis successfully identified the optimal growing location for each crop based on the aggregated performance score. For example, the best location for Potato is Rural_Sokoto, while for Rice, it's Rural_Hawassa.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scipy
* Statsmodels
