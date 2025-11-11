

# 📱 Mobile Price Prediction Web App

![Python](https://img.shields.io/badge/Python-3.11-blue) ![Streamlit](https://img.shields.io/badge/Streamlit-v1.30-orange) ![License](https://img.shields.io/badge/License-MIT-green) ![GitHub issues](https://img.shields.io/github/issues/UsamaMunawarr/mobile-price-predictor) ![GitHub stars](https://img.shields.io/github/stars/UsamaMunawarr/mobile-price-predictor)

![App Screenshot](images/p1.PNG)
*A preview of the Mobile Price Predictor app.*

---

## Overview

The **Mobile Price Prediction App** is a **multi-model machine learning web application** built with **Streamlit**, designed to predict the prices of smartphones based on their specifications.

Key highlights:

* Input mobile specifications to predict price.
* Compare predictions with similar models.
* Explore interactive data visualizations.
* Evaluate multiple ML models to identify the best performer.

This project demonstrates a full **data science workflow**: **web scraping → preprocessing → model training → deployment**.

---

## 🚀 Features

### 🏠 Price Prediction

* Predict prices based on specs: Brand, OS, RAM, Storage, Camera, Battery, GPU, and more.
* Models available:

  * **XGBoost**
  * **Random Forest**
  * **Linear Regression**
  * **Stacking Ensemble** (multi-model approach for improved accuracy)
* Shows **similar models** with images and specs for reference.

### 📊 Data Analysis

* Average price by brand.
* Interactive **heatmaps** of feature correlations.
* Scatter plots for **Battery vs Price** trends.
* 3D visualization: RAM, Storage & Price interactions.

### 📈 Model Evaluation

* Compare models on **R², MAE, RMSE**.
* Interactive **bar charts** for error comparison.
* Automatic **best model detection**.
* View **detailed ranking table** for all models.

### 👨‍💻 About

* Developer: **Usama Munawar** – Data Scientist | MPhil Scholar | ML Enthusiast
* Connect via GitHub, LinkedIn, YouTube, Twitter, and Facebook.

---

## 🛠️ Technologies & Libraries

* **Python 3.11**
* **Streamlit** for interactive web app
* **Pandas, NumPy** for data handling
* **Scikit-learn, XGBoost** for ML models
* **Joblib** for model serialization
* **Plotly & Seaborn** for interactive visualizations
* **PIL** for image processing

---

## 📁 Project Structure

```
mobile-price-predictor/
│
├─ app.py                        # Streamlit app
├─ mobiles_prices_prediction.csv  # Dataset
├─ xgboost_model.pkl
├─ stacking_ensemble_model.pkl
├─ random_forest_model.pkl
├─ linear_regression_model.pkl
└─ README.md
```

---

## 🧠 Workflow

1. **Web Scraping**: Collected mobile specs & prices.
2. **Data Preprocessing**: Cleaned, handled missing values, standardized features.
3. **Model Training**: Multiple regression models including **stacking ensemble**.
4. **Deployment**: Built **Streamlit web app** with interactive pages.

---

## 📸 Screenshots



> ### Price Prediction Page
![Price Prediction](images/p2.PNG)
![Price Prediction](images/p3.PNG)
> ### Data Analysis Page
![Data Analysis](images/Pa.PNG)
![Data Analysis](images/pb.PNG)
![Data Analysis](images/pc.PNG)
![Data Analysis](images/pd.PNG)
> ### Model Evaluation Page
![Model Evaluation](images/c1.PNG)
![Model Evaluation](images/c2.PNG)
![Model Evaluation](images/c3.PNG)

> ### About Page
![About Page](images/d2.PNG)

---

## 🔧 Run Locally

```bash
# Clone the repo
git clone https://github.com/UsamaMunawarr/mobile-price-predictor.git

# Navigate to the project
cd mobile-price-predictor

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 📈 Future Improvements

* Add **user authentication**.
* Integrate **Neural Networks** for price prediction.
* Enable **real-time web scraping** for updated mobile prices.
* Add **export functionality** for predicted prices & analysis reports.

---

## 🌐 Connect with Me

[![GitHub](https://img.icons8.com/fluent/48/000000/github.png)](https://github.com/UsamaMunawarr)[![LinkedIn](https://img.icons8.com/color/48/000000/linkedin.png)](https://www.linkedin.com/in/abu--usama)[![YouTube](https://img.icons8.com/?size=50\&id=19318\&format=png)](https://www.youtube.com/@CodeBaseStats)[![Twitter](https://img.icons8.com/color/48/000000/twitter.png)](https://twitter.com/Usama__Munawar?t=Wk-zJ88ybkEhYJpWMbMheg&s=09)[![Facebook](https://img.icons8.com/color/48/000000/facebook-new.png)](https://www.facebook.com/profile.php?id=100005320726463&mibextid=9R9pXO)

---


