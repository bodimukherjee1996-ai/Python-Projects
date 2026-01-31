# 🏠 Airbnb NYC Pricing & Demand Prediction using Machine Learning

## 📌 Project Overview
Pricing Airbnb listings correctly is critical for maximizing revenue and bookings.
This project analyzes Airbnb NYC 2019 data and builds machine learning models to:

- Understand key drivers of listing prices
- Identify factors influencing booking demand
- Predict optimal prices and high-demand listings using ML

The project combines **exploratory data analysis, feature engineering, regression,
classification, and business insights** into an end-to-end analytics solution.

---

## 🎯 Business Objectives
- Analyze how location, property type, and host behavior affect pricing
- Predict nightly listing prices using regression models
- Classify listings into **high-demand vs low-demand** categories
- Translate ML outputs into actionable business recommendations

---

## 📂 Dataset
- **Source:** Airbnb NYC 2019 dataset  
- **Observations:** ~49,000 listings  
- **Key Features:**
  - Location (latitude, longitude, neighbourhood)
  - Property & room type
  - Host portfolio size
  - Reviews and engagement metrics
  - Availability and pricing information

---

## 🧹 Data Cleaning & Feature Engineering
Key preprocessing steps:
- Handled missing values using business-sensible defaults
- Log-transformed price to reduce skewness
- Engineered demand and engagement features
- Encoded categorical variables using one-hot encoding
- Removed extreme price outliers for stability

---

## 🔍 Exploratory Data Analysis (EDA)
Key findings:
- Manhattan listings command the highest average prices
- Entire homes are priced significantly higher than shared or private rooms
- A small number of hosts control a large share of listings
- Review activity strongly correlates with booking demand

---

## 🤖 Machine Learning Models

### 🔹 Price Prediction (Regression)
| Model | Purpose | Metric |
|------|--------|--------|
| Linear Regression | Baseline | RMSE |
| Random Forest Regressor | Final Model | Lower RMSE |

📌 **Random Forest outperformed Linear Regression**, indicating strong non-linear
pricing dynamics.

---

### 🔹 Demand Prediction (Classification)
- Framed demand as a binary classification problem
- Used review activity as a proxy for booking demand
- Evaluated using:
  - Confusion Matrix
  - Precision, Recall, F1-Score

📌 Review frequency and location emerged as the strongest demand drivers.

---

## 📊 Model Evaluation

### Price Prediction
- Random Forest achieved significantly lower RMSE than the baseline
- Captured complex interactions between location, room type, and engagement

### Demand Classification
- High recall for high-demand listings
- Suitable for identifying listings with strong booking potential

---

## 🔎 Feature Importance Insights
- **Pricing Drivers:** Location, room type, host portfolio size
- **Demand Drivers:** Reviews per month, total reviews, location
- Pricing and demand are influenced by **different factors**

---

## 💡 Business Insights & Recommendations
- Location sets the price ceiling, but reviews drive demand
- Hosts should prioritize early guest satisfaction to build demand
- Entire homes benefit from premium pricing strategies
- ML-based pricing outperforms static pricing rules

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn, Plotly
- **ML Models:** Linear Regression, Random Forest
- **Platform:** Google Colab / Jupyter Notebook

---

## 🚀 Future Improvements
- Incorporate seasonality and time-based demand
- Add dynamic pricing recommendations
- Use SHAP for advanced model explainability
- Extend demand prediction to multi-class segmentation

---

## 👤 Author
**Bodhisatva Mukherjee**  
📍 Bengaluru, India  
