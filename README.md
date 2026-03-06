# Weather Type Classification using Machine Learning

## Project Overview

This project focuses on building a **machine learning model to classify weather types** based on various meteorological features such as temperature, humidity, wind speed, precipitation, atmospheric pressure, UV index and visibility.

The goal is to train multiple classification models and compare their performance to determine the most effective model for predicting weather conditions.


## Dataset

The dataset contains **13,200 rows and 11 columns** including weather-related features and the target variable.

### Features

**Numerical Features**

* Temperature
* Humidity
* Wind Speed
* Precipitation (%)
* Atmospheric Pressure
* UV Index
* Visibility (km)

**Categorical Features**

* Cloud Cover
* Season
* Location

**Target Variable**

* Weather Type (Rainy, Cloudy, Sunny, Snowy)


## Exploratory Data Analysis

Some key observations from the dataset:

* Temperature ranges from **-25°C to 109°C**
* Humidity includes values **greater than 100% (outliers)**
* Wind Speed and Precipitation contain **extreme values**
* Visibility ranges between **0 km and 20 km**
* Weather Type distribution is **balanced with 3,300 records for each class**

### Correlation Insights

* **Temperature and UV Index** show positive correlation.
* **Humidity and Precipitation** are strongly correlated.
* **Wind Speed and Humidity** show negative correlation.


## Machine Learning Models Used

The following classification algorithms were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest


## Model Performance

Model performance was evaluated using **Accuracy Score**.

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~0.84    |
| KNN                 | ~0.88    |
| Decision Tree       | ~0.90    |
| Random Forest       | ~0.91    |



## Best Model

Among all models **Random Forest achieved the highest accuracy (~91%)** making it the most suitable model for this weather classification task.


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn


## Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Final Prediction


## Conclusion

Multiple machine learning models were trained to classify weather conditions.
The **Random Forest classifier achieved the highest accuracy**, demonstrating its effectiveness for predicting weather types based on meteorological data.


