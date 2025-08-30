# 🌞 Renewable Energy Generation Forecast

## 📌 Project Objective
The objective of this project is to analyze and identify key factors that impact the efficiency of a solar power plant.  
Using historical data (DC_POWER, AC_POWER) and environmental conditions (IRRADIATION, MODULE_TEMPERATURE),  
the goal is to find which variables affect performance the most and detect potential inefficiencies.

---

## 📂 Dataset
- **Source:** [Solar Power Generation Data (Kaggle)](https://www.kaggle.com/datasets/anikannal/solar-power-generation-data)  
- **Format:** CSV  
- **Features:**  
  - `AMBIENT_TEMPERATURE (°C)` – surrounding temperature  
  - `MODULE_TEMPERATURE (°C)` – panel operating temperature  
  - `DC_POWER (kW)` – direct current power  
  - `AC_POWER (kW)` – alternating current power  
  - `DAILY_YIELD (kWh)` – daily cumulative energy generation  
  - `TOTAL_YIELD (kWh)` – total plant generation  

---

## ✅ Week-1 Work (Completed)
- Imported dataset and libraries  
- Data exploration (`.head()`, `.info()`, `.describe()`)  
- Checked missing values  
- Feature engineering on `DATE_TIME` (Hour, Day, Month)  
- Visualizations:  
  - Daily Yield vs Time  
  - AC vs DC Power  
  - Power by Hour of Day  
  - Correlation Heatmap  
  - Feature Distributions  
- Train-Test Split (80-20)  

📌 **Commit:** Published Week-1 work for GitHub submission  

---

## 👨‍💻 About
This project is maintained by **Saurabh Kumar Maurya** as part of mentor-guided learning.  
Progress will be updated **week by week** (Week-2: model training & evaluation, Week-3: deployment, etc.).  

---
