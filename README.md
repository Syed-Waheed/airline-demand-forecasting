<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=260&section=header&text=Airline%20Demand%20Forecasting&fontSize=70&animation=fadeIn&fontAlignY=38&desc=Machine%20Learning%20•%20Booking%20Conversion%20•%20Streamlit&descAlignY=55&descAlign=50" alt="Airline Demand Header" />

  <br />

  <p>
    <img src="https://img.shields.io/badge/XGBoost-Gradient_Boosting-FLAT?style=for-the-badge&logo=xgboost&logoColor=white&color=red" alt="XGBoost" />
    <img src="https://img.shields.io/badge/Scikit_Learn-Machine_Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit Learn" />
    <img src="https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
    <img src="https://img.shields.io/badge/Imbalanced_Learn-SMOTE-blue?style=for-the-badge" alt="SMOTE" />
  </p>

  <h3>✈️ Predicting the Skies with Data</h3>
  
  <p align="center">
    <i>"An end-to-end machine learning solution that predicts flight booking conversions and estimates passenger demand to optimize airline operations."</i>
  </p>
</div>

---

## 📌 Mission Overview

In the highly competitive aviation industry, understanding passenger behavior is key. This project utilizes **Machine Learning** to forecast:
1.  **Booking Conversion Probability:** Will a user complete their booking?
2.  **Passenger Demand:** How many passengers are expected on a specific route?

We solved critical challenges like **class imbalance** using SMOTE and deployed the final model as an **interactive Streamlit web application**.

---

## 📸 Dashboard Preview

<div align="center">
  <img src="output/Output.png" alt="Streamlit Dashboard" width="800" style="border-radius: 10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);" />
  <p><i>Real-time prediction interface visualizing booking trends and demand factors.</i></p>
</div>

---

## 🚀 Key Features

- ✅ **Dual Prediction Engine**: Estimates both Booking Probability (Classification) and Total Passengers (Regression).
- 📊 **Interactive Dashboard**: Powered by Streamlit for real-time scenario testing.
- 🧠 **Advanced Modeling**: Ensembled **Random Forest** & **XGBoost** for maximum accuracy.
- ⚖️ **Imbalance Handling**: Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to fix skewed booking data.
- 🔍 **Feature Intelligence**: Route analysis, flight duration, and seasonal pattern detection.

---

## 🛠️ The ML Pipeline

This project follows a production-ready workflow:

1.  **Data Ingestion**: Merging `British Airways Schedule` with `Customer Booking Data` (10,000+ records).
2.  **Preprocessing**: Cleaning nulls, encoding categorical variables, and handling outliers.
3.  **Feature Engineering**: Creating "Haul Type", "Route Demand", and "Seasonality" features.
4.  **Modeling**: Training Random Forest & XGBoost with Hyperparameter Tuning.
5.  **Evaluation**: rigorous testing on unseen data.
6.  **Deployment**: Serving the model via a Streamlit frontend.

---

## 📊 Model Performance

Our models achieved high reliability on the test set:

| Metric | Score | Performance Verdict |
| :--- | :--- | :--- |
| **Accuracy** | **90%+** | 🟢 Excellent |
| **R² Score** | **0.79** | 🟢 Strong Correlation |
| **MAE** | **2.36** | 🟢 Low Error Margin |

---
## 🛠 Tech Stack
| Component | Technology | Description |
| :--- | :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python) | Core Logic |
| **ML Algorithms** | ![XGBoost](https://img.shields.io/badge/-XGBoost-black?style=flat-square) ![RandomForest](https://img.shields.io/badge/-Random_Forest-black?style=flat-square) | Predictive Modeling |
| **Frontend** | ![Streamlit](https://img.shields.io/badge/-Streamlit-black?style=flat-square&logo=streamlit) | Web App Interface |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/-Pandas-black?style=flat-square&logo=pandas) | Data Manipulation |
| **Balancing** | ![SMOTE](https://img.shields.io/badge/-SMOTE-black?style=flat-square) | Handling Class Imbalance |

---

## ⚙️ Installation & Setup

```bash
# 1. Clone the repository
git clone [https://github.com/Syed-Waheed/Airline-Booking-Conversion-Prediction.git](https://github.com/Syed-Waheed/Airline-Booking-Conversion-Prediction.git)

# 2. Navigate to project directory
cd Airline-Booking-Conversion-Prediction

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch the Dashboard
streamlit run app.py
```
---
## 📎 Acknowledgements & 👤 Author

- **British Airways** for the dataset context  
- **Forage** for the virtual internship framework  
- **Streamlit Community** for deployment resources  

<div align="left">
  <img src="https://github.com/Syed-Waheed.png" width="100" align="left" style="margin-right: 20px; border-radius: 50%;" alt="Syed Abdul Waheed" />

  <strong>Syed Abdul Waheed</strong><br/>
  <em>Data Science Enthusiast | Python Developer | Automation Explorer</em>

  Focused on building robust ML pipelines and turning data into business value.

  <br /><br />

  <a href="https://www.linkedin.com/in/syed-abdul-waheed/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Syed-Waheed">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
</div>

<br clear="left"/>

<div align="center">
</div>

---
