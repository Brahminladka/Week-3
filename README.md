# 🌞 Solar Power Prediction

This project predicts **solar power generation (kW)** based on meteorological and environmental parameters using **Linear Regression**. The model helps in estimating renewable energy output for efficient energy management.

---

## 📌 Project Overview
The goal of this project is to:
- Analyze weather and solar irradiance data.
- Perform data cleaning (outlier detection, missing value handling).
- Train a **Linear Regression model** to predict solar power generation.
- Visualize correlations and prediction accuracy.

---

## 📂 Dataset
The dataset contains **4213 records with 21 features**, including:
- Temperature, humidity, pressure, precipitation, snowfall.
- Cloud cover (total, high, medium, low).
- Wind speed & direction (multiple levels).
- Solar angles (azimuth, zenith, angle of incidence).
- **Target variable:** `generated_power_kw`.

📄 Example columns:
- `temperature_2_m_above_gnd`
- `relative_humidity_2_m_above_gnd`
- `shortwave_radiation_backwards_sfc`
- `wind_speed_80_m_above_gnd`
- `generated_power_kw` (output)

---

## ⚙️ Installation
# Install required dependencies
pip install pandas numpy seaborn scikit-learn matplotlib

## 🚀 Usage
# Clone the repository and open the Jupyter Notebook
git clone <repo-url>
cd solar-power-prediction
jupyter notebook solar_power_prediction.ipynb

# Run all cells to:
# - Load and preprocess data
# - Train Linear Regression model
# - Evaluate predictions

## 🧹 Data Preprocessing
# - Outlier removal using IQR method
# - Feature exploration & correlation analysis
# - Normalization and splitting dataset into train/test sets

## 📊 Model Training
# - Algorithm: Linear Regression
# - Metrics Used: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score
# - Visualizations: Pairplots, heatmaps, regression plots

## 📈 Results
# - The model achieves good performance in predicting solar power based on environmental variables
# - Predictions follow real-world trends with small error margins
# - Correlation shows solar irradiance & angles as key predictors
