# 🌦️ Weather Prediction

A Machine Learning project that predicts weather conditions based on environmental and geographical features.

## 📌 Project Overview

This project uses Machine Learning classification algorithms to predict one of four weather types:

* ☁️ Cloudy
* 🌧️ Rainy
* ❄️ Snowy
* ☀️ Sunny

The dataset contains **13,200 records** and **11 features**, including temperature, humidity, wind speed, precipitation, cloud cover, atmospheric pressure, UV index, season, visibility, and location.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* Gradio

## 🔄 Project Workflow

1. Data loading and exploration
2. Data preprocessing
3. Categorical feature encoding
4. Feature scaling using StandardScaler
5. Train-test split
6. Training multiple Machine Learning models
7. Model evaluation and comparison
8. Building an interactive Gradio interface

## 🤖 Machine Learning Models

| Model                |   Accuracy |
| -------------------- | ---------: |
| Gaussian Naive Bayes |     95.51% |
| Logistic Regression  |     92.34% |
| SVM Linear           |     96.19%|
| **SVM RBF**              | **96.71%** |

🏆 **SVM achieved the highest accuracy of 96.71%.**

## 🚀 Live Demo

👉 **https://944507756be19b2609.gradio.live**

The interactive Gradio interface allows users to enter weather conditions and get a predicted weather type.

## 📂 Files

* `weather-prediction.ipynb` — Complete project notebook
* `seattle-weather.csv` — Dataset

## 🎯 Conclusion

The project demonstrates how Machine Learning can be used to classify weather conditions. Among the tested models, **SVM performed the best**, achieving an accuracy of **90.72%**.

