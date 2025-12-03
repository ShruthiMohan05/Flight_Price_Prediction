# 🛫 Flight Price Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Library](https://img.shields.io/badge/Library-Scikit_Learn%20|%20XGBoost-orange)
![License](https://img.shields.io/badge/License-MIT-green)

An end-to-end Machine Learning project that predicts flight ticket prices based on travel features like airline, journey duration, stops, and class. This project compares multiple regression models to find the most accurate pricing engine.

## 📊 Project Overview
Predicting flight prices is a complex regression problem due to dynamic pricing strategies used by airlines. This repository analyzes flight data to understand key price drivers and builds a robust predictive model.

**Key Objectives:**
* Perform Exploratory Data Analysis (EDA) to visualize price trends.
* Preprocess categorical travel data (Airline, Source, Destination).
* Train and evaluate models: **Linear Regression, Random Forest, XGBoost**.
* Achieve high prediction accuracy for unseen data.

## 📂 Dataset
The dataset contains information on flight booking options in India.
* **Source**: [Kaggle Flight Price Prediction Dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)
* **Features**: Airline, Flight Code, Source City, Departure Time, Stops, Arrival Time, Destination City, Class, Duration, Days Left.
* **Target**: Price

## 🛠️ Tech Stack
* **Language**: Python 3.11
* **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib

## 🚀 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone [https://github.com/yourusername/Flight-Price-Prediction.git](https://github.com/yourusername/Flight-Price-Prediction.git)
   cd Flight-Price-Prediction
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Notebook Open notebooks/ml-project-final(1).ipynb to see the full analysis and training process.

 ## 🎯 Results
We trained 3 models. **Random Forest and XGBoost** performed the best with ~98% accuracy.

| Model | Accuracy (R2) |
|-------|---------------|
| Linear Regression | 91% |
| Random Forest | 98% |
| XGBoost | 98% |

📊 Visuals

Price Distribution
Distribution of ticket prices showing a right-skewed trend.

Correlation Heatmap
Correlation between different features and price.
