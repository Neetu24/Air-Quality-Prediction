# 🌫️ Air Quality Prediction Using Machine Learning

## 📌 Project Description

This project focuses on predicting air quality levels using historical data and time-series forecasting techniques. We use Facebook Prophet to forecast pollutant concentration—specifically **CO(GT)**—based on hourly sensor data. The dataset includes air pollutant levels and meteorological variables.

---

## 🧠 Technologies Used

- **Python**
- **Google Colab**
- **Pandas**, **NumPy** (data manipulation)
- **Matplotlib**, **Seaborn** (visualization)
- **Scikit-learn** (scaling, metrics)
- **Facebook Prophet** (forecasting)

---

## 📁 Dataset

- **Name**: Air Quality Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/360/air+quality)
- **File**: `AirQualityUCI.csv`
- **Details**: Contains hourly averaged responses from air quality chemical sensors.

---

## 🚀 How to Run the Project

1. **Open** the provided `.ipynb` file in **Google Colab**.
2. **Upload** the dataset (`AirQualityUCI.csv`) when prompted.
3. Run all the cells sequentially to:
   - Clean and preprocess the data
   - Forecast CO(GT) levels using Facebook Prophet
   - Evaluate the model
   - Visualize actual vs predicted values

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Merged `Date` and `Time` into a single `Datetime` column
   - Handled missing/invalid values (e.g., `-200`)
   - Scaled features using `StandardScaler`

2. **Model Building**
   - Used `fbprophet` to forecast `CO(GT)` concentrations
   - Split data into training and testing sets (80-20)
   - Forecasted for the test period

3. **Model Evaluation**
   - Evaluated using:
     - Mean Absolute Error (MAE)
     - Root Mean Square Error (RMSE)
     - R-squared Score (R²)
   - Visualized predicted vs actual pollutant levels

---

## 📊 Evaluation Metrics (Sample Output)

MAE: 0.3957
RMSE: 0.4918
R2 Score: 0.6521

---

## 📈 Visualizations

- Forecast plot generated using `fbprophet`
- Actual vs. Predicted CO(GT) over time using `matplotlib`

---

## 📦 Folder Structure

Air_Quality_Prediction/
│
├── Air_Quality_Prediction.ipynb 
├── AirQualityUCI.csv
└── README.md


---

## ✨ Optional Extensions

- Predict other pollutants: NOx(GT), NO2(GT)
- Use deep learning (e.g., LSTM)
- Build an interactive dashboard (Streamlit, Plotly)

---

## 👩‍💻 Author

- **Name**: B Nitya Santoshini Reddy
- **Project Type**: Machine Learning Capstone

---


