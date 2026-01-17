# Air-Quality-Prediction
### 📋 Overview
This project analyzes historical air quality data to understand pollution trends and predict Air Quality Index (AQI) levels. It processes environmental factors such as Sulphur Dioxide (SO2), Nitrogen Dioxide (NO2), and Respirable Suspended Particulate Matter (RSPM) to classify air quality and forecast pollution levels using Machine Learning.

### 🧠 Key Features
* **Data Cleaning:** Handling missing values (NaN) in sensor data (`stn_code`, `agency`, `pm2_5`).
* **Exploratory Data Analysis (EDA):**
    * Visualizing correlations between pollutants using `Seaborn` pairplots.
    * Distribution analysis of SO2 and NO2 levels across different states.
* **Predictive Modeling:** Implements regression algorithms to predict AQI based on pollutant concentrations.
    * *Linear Regression* (Baseline)
    * *Random Forest Regressor* (For capturing non-linear patterns)
    * *Decision Tree Regressor*

### 📂 Dataset
The analysis uses `data.csv`, which contains:
* **Pollutants:** `so2`, `no2`, `rspm`, `spm`, `pm2_5`
* **Metadata:** `state`, `location`, `sampling_date`, `type` (Industrial/Residential)

### 💻 Tech Stack
* **Language:** Python 3.10+
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `seaborn`, `matplotlib`
* **Machine Learning:** `scikit-learn`

### 🚀 How to Run
1.  Install dependencies:
    ```bash
    pip install pandas numpy seaborn scikit-learn matplotlib
    ```
2.  Launch the notebook:
    ```bash
    jupyter notebook "Air_Quality_Index_Prediction.ipynb"
    ```

### 📊 Results
The project evaluates models using **Mean Absolute Error (MAE)** and **R² Score** to determine the most accurate predictor for air quality monitoring.# Air-Quality-Prediction

