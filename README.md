⚡ Household Energy Consumption Analysis and Prediction
📘 Overview
This project analyzes household electricity consumption data to uncover patterns of energy usage and identify the most power-intensive areas of a home.
The dataset includes measurements such as active power, voltage, current intensity, and sub-metering values for kitchen, laundry, and HVAC (AC / water heater) appliances.
The goal is to perform Exploratory Data Analysis (EDA), visualize energy patterns, and build a Linear Regression model to predict future energy consumption.

🎯 Objectives
Analyze daily and hourly electricity consumption patterns.
Identify which household areas contribute most to overall energy usage.
Examine correlations between voltage, current, and power consumption.
Develop a predictive model to estimate future energy demand.

📊 Dataset

Source: https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set

Attributes:

Global_active_power — average active power (kW)

Global_reactive_power — reactive power (kW)

Voltage — average voltage (V)

Global_intensity — current intensity (A)

Sub_metering_1 — kitchen appliances

Sub_metering_2 — laundry appliances

Sub_metering_3 — water heater & air conditioner

🧠 Workflow

Data Cleaning:
Convert date/time to datetime
Handle missing values and convert text to numeric

Exploratory Data Analysis (EDA):
Visualize daily and hourly usage trends
Compare consumption by area (sub-metering)
Compute correlations between power, voltage, and current

Modeling (Regression):
Train a Linear Regression model to predict Global_active_power
Evaluate with RMSE and R² Score
Visualize actual vs predicted values

Insight Extraction:
Identify high-consumption hours and appliances
Recommend energy-efficiency improvements

🧰 Tech Stack
Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Tools: Jupyter Notebook / Google Colab, Power BI / Looker Studio
Visualization: Correlation heatmaps, trend lines, area consumption charts

📈 Results & Insights
Strong positive correlation between current intensity and active power (r ≈ 1.0)
High energy usage from Sub_metering_3 (water heater + AC)
Negative correlation between voltage and power usage, indicating voltage drops during heavy loads
Regression model achieved:
RMSE: ~0.03 kW
R²: ~0.94 (example — adjust with your result)

🚀 Key Skills Demonstrated
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Linear Regression Modeling
Data Visualization & Interpretation
Feature Correlation Analysis
Insight Communication

💡 Future Improvements
Implement time-series forecasting (ARIMA / LSTM)
Build an interactive dashboard for real-time monitoring
Automate anomaly detection for unusual consumption patterns

👨‍💻 Author
Rafli Maulana Andika
Data Science Enthusiast | Machine Learning & Visualization
