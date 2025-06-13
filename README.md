# Australian Weather Data Analysis 🌤️

This project presents a comprehensive analysis of historical weather data across various regions in Australia. The objective is to derive meaningful insights from meteorological variables and identify patterns related to temperature, rainfall, humidity, and other climatic factors.

The analysis is conducted using Python and industry-standard data science libraries, with a focus on data cleaning, exploratory data analysis (EDA), and visual storytelling.

---

## 🧭 Objectives

- Explore and understand key weather trends in Australia.
- Perform data cleaning and preprocessing to handle missing and anomalous values.
- Visualize distributions, correlations, and seasonal behavior of weather variables.
- Identify potential predictors for future weather conditions (e.g., rainfall).
- Establish a foundation for future predictive modeling or forecasting efforts.

---

## 📂 Project Structure

📦 Australian Weather Data Analysis
├── FinalProject_AUSWeather.ipynb # Main Jupyter notebook with all analyses
├── data/
│ └── weatherAUS.csv # (Assumed) primary dataset
├── images/ # Exported plots and visualizations
├── README.md # Project documentation
└── requirements.txt # Python dependencies

---

## 🛠️ Technologies Used

- **Programming Language**: Python 3.x
- **Libraries & Tools**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn`, `plotly` – Data visualization
  - `scikit-learn` – Feature analysis and modeling foundations
  - `Jupyter Notebook` – Interactive analysis and presentation

---

## 📊 Data Summary

The dataset contains daily weather observations from multiple Australian locations and includes features such as:

- `Date`, `Location`
- `MinTemp`, `MaxTemp`
- `Rainfall`, `RainToday`, `RainTomorrow`
- `Humidity9am`, `Humidity3pm`
- `WindGustSpeed`, `WindSpeed9am`, `WindSpeed3pm`
- `Pressure9am`, `Pressure3pm`
- `Cloud9am`, `Cloud3pm`
- `Temp9am`, `Temp3pm`

The target variable for potential classification tasks is **`RainTomorrow`**, indicating whether or not it will rain the next day.

---

## 📈 Key Insights

- Visualized rainfall and temperature distributions across various cities and seasons.
- Conducted correlation analysis to uncover relationships between humidity, pressure, and rainfall.
- Identified regional weather patterns that could inform local forecasting efforts.
- Handled significant missing data using imputation and filtering techniques.

---

## 🚀 Getting Started

### Prerequisites

Install required libraries using:

```bash
pip install -r requirements.txt
