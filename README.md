# 🏠 HDB Resale Price Analysis and Prediction

An end-to-end data analytics and machine learning project that investigates the key factors influencing Housing & Development Board (HDB) resale prices in Singapore. This project integrates multiple public datasets, geospatial information, and macroeconomic indicators to build predictive models and generate actionable insights for property valuation.

---

## 📖 Overview

Housing prices are affected by a combination of property attributes, accessibility, economic conditions, and government policies. This project aims to identify these factors through data-driven analysis and develop predictive models for estimating HDB resale prices.

The project covers the complete analytics workflow, including data preprocessing, feature engineering, exploratory data analysis (EDA), statistical analysis, predictive modelling, and model evaluation.

---

## 🎯 Objectives

- Identify key drivers of HDB resale prices.
- Engineer meaningful location-based and macroeconomic features.
- Evaluate the impact of accessibility, amenities, interest rates, and government cooling measures.
- Develop predictive models for HDB resale price estimation.
- Generate actionable insights to support housing-related decision making.

---

## 📂 Datasets

This project integrates multiple public datasets:

| Dataset | Description |
|----------|-------------|
| HDB Resale Transactions | Historical HDB resale transaction records |
| MRT Stations | Locations of MRT stations for accessibility analysis |
| Shopping Malls | Locations of shopping malls |
| Interest Rates | Historical mortgage interest rates |
| Government Cooling Measures | Policy implementation timeline |
| OneMap API | Geocoding and distance calculations |

---

## ⚙️ Methodology

### 1. Data Collection
- Integrated multiple public datasets
- Retrieved geospatial information using the OneMap API

### 2. Data Preprocessing
- Data cleaning
- Missing value handling
- Duplicate removal
- Feature transformation

### 3. Feature Engineering
- Distance to nearest MRT station
- Distance to nearest shopping mall
- Property age
- Remaining lease
- Interest rate indicators
- Government cooling measures
- Location-based features

### 4. Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Trend analysis
- Price comparison across towns

### 5. Predictive Modelling
- Multiple Linear Regression
- Random Forest Regressor

### 6. Model Evaluation
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Feature importance analysis

---

## 📊 Key Findings

- Proximity to MRT stations is one of the strongest determinants of HDB resale prices.
- Larger floor areas generally command higher resale values.
- Government cooling measures influence market behaviour.
- Interest rate fluctuations affect housing affordability and resale prices.
- Combining geospatial and macroeconomic features improves predictive performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- OneMap API
- Jupyter Notebook

---

## 📁 Project Structure

```text
.
├── Data/
│   ├── Raw Data/
│   └── Processed Data/
│
├── Notebooks/
│   ├── Data_Preprocessing.ipynb
│   ├── Feature_Engineering.ipynb
│   ├── Exploratory_Data_Analysis.ipynb
│   └── Model_Development.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/jjianhhao/SC3021.git
cd SC3021
```

2. Install the required dependencies

3. Open the notebooks using Jupyter Notebook or VS Code.

4. Execute the notebooks in sequence.

---

## 💡 Skills Demonstrated

- Data Cleaning & Preprocessing
- Feature Engineering
- Geospatial Analytics
- Exploratory Data Analysis
- Statistical Analysis
- Machine Learning
- Model Evaluation
- Data Visualization
- Business Analytics

---

## 🔮 Future Improvements

- Experiment with XGBoost and LightGBM models.
- Develop an interactive web application for price prediction.
- Automate the data pipeline for real-time updates.
- Incorporate additional socioeconomic and demographic features.

---

## 👥 Contributors

- Jian Hao
- SC3021 Project Group 9

---

## 📜 License

This project was completed as part of **SC3021** at **Nanyang Technological University (NTU)**.
