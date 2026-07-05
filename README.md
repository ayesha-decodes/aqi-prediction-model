# 🌍 Air Quality in India: Pollution Trends, AQI Analysis & Prediction

A Machine Learning and Data Analysis project that explores air pollution trends across Indian cities and predicts the **Air Quality Index (AQI)** using environmental pollutant data.

---

## 📖 Project Overview

Air pollution is one of the most significant environmental and public health challenges in India. This project analyzes historical air quality data from multiple Indian cities, identifies pollution trends, performs feature engineering, and builds a **Random Forest Regression Model** to predict the Air Quality Index (AQI).

The notebook covers the complete data science workflow, including:

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Machine Learning Model Training
- Model Evaluation
- Model Saving & Loading
- AQI Prediction

---

## 🎯 Objectives

- Analyze air pollution levels across Indian cities
- Explore seasonal and yearly pollution trends
- Identify relationships among pollutants
- Build a regression model to predict AQI
- Evaluate model performance
- Save and reload the trained model for future predictions

---

## 📂 Dataset

**Dataset:** Air Quality Data in India

The dataset contains daily air quality measurements collected from monitoring stations across different Indian cities.

### Features

- City
- Date
- PM2.5
- PM10
- NO
- NO₂
- NOx
- NH₃
- CO
- SO₂
- O₃
- Benzene
- Toluene
- Xylene
- AQI
- AQI Bucket

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Dataset Overview
- Data Types
- Missing Value Analysis
- Duplicate Record Detection
- Statistical Summary
- AQI Distribution
- Top Polluted Cities
- Seasonal AQI Analysis
- Yearly Pollution Trend
- Correlation Heatmap
- Pollutant Relationship Analysis

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Date conversion
- Missing value imputation
- Feature Engineering
- Season extraction
- Year, Month and Day extraction
- AQI Bucket Encoding
- One-Hot Encoding of categorical variables

---

## 📈 Feature Engineering

New features created include:

- Year
- Month
- Day
- Season
- AQI Bucket Encoding

These engineered features help improve model performance by capturing temporal and seasonal pollution patterns.

---

## 🤖 Machine Learning Model

### Algorithm Used

- 🌲 Random Forest Regressor

---

## 📊 Model Evaluation

The model is evaluated using:

- Mean Absolute Error (MAE)
- R² Score

---

## 📷 Visualizations

The notebook generates the following visualizations:

- 📊 AQI Distribution
- 🌍 Top Polluted Cities
- 📈 Yearly AQI Trend
- 📅 Seasonal AQI Distribution
- 🔥 Correlation Heatmap
- 📉 Pollutant Relationships

---

## 📁 Project Structure

```text
Air-Quality-Analysis/
│
├── aqi_project.ipynb
├── random_forest_aqi_model.pkl
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Air-Quality-Analysis.git
```

Move into the project directory

```bash
cd Air-Quality-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## ▶️ How to Run

1. Open the notebook.
2. Download the dataset using KaggleHub.
3. Run all notebook cells sequentially.
4. Perform Exploratory Data Analysis.
5. Train the Random Forest Regression model.
6. Evaluate model performance.
7. Save the trained model.
8. Load the model and predict AQI for new data.

---

## 📈 Workflow

```text
Download Dataset
        │
        ▼
Load Data
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Random Forest Regression
        │
        ▼
Model Evaluation
        │
        ▼
Save Model
        │
        ▼
Load Model
        │
        ▼
Predict AQI
```

---

## 📊 Results

The Random Forest Regression model successfully predicts Air Quality Index (AQI) using pollutant concentration data and engineered temporal features.

The project also highlights:

- Seasonal variations in AQI
- Most polluted cities
- Relationships between pollutants
- Feature importance for AQI prediction

---

## 💾 Model Persistence

The trained model is saved using **Pickle**, allowing it to be reused without retraining.

```python
import pickle

pickle.dump(model, open("random_forest_aqi_model.pkl", "wb"))
```

Load the model:

```python
model = pickle.load(open("random_forest_aqi_model.pkl", "rb"))
```

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- XGBoost Regression
- LightGBM Regression
- CatBoost Regression
- Cross Validation
- Interactive Dashboard using Streamlit
- Real-time AQI Prediction
- Weather API Integration
- Air Pollution Forecasting
- Deep Learning Models (LSTM)

---

## 📚 Learning Outcomes

This project demonstrates:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Regression Modeling
- Model Evaluation
- Model Persistence
- Predictive Analytics

---

## 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
pickle
kagglehub
jupyter
```

Install all dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub jupyter
```

---

## 👩‍💻 Author

**Ayesha Nagma**

Machine Learning • Data Science • Python • SQL • Data Analytics

---

## ⭐ Support

If you found this project useful, please consider giving the repository a **⭐ Star** on GitHub.

Your support helps improve future open-source projects and encourages continued development.
