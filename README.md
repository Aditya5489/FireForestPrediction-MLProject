# 🔥 Fire Weather Index (FWI) Prediction using Algerian Forest Fire Dataset

## 🌲 Project Overview
This Machine Learning project predicts the **Fire Weather Index (FWI)** — a key indicator of fire risk — using the **Algerian Forest Fire Dataset**.  
The dataset contains meteorological and fire weather parameters collected from different regions of Algeria, which are used to estimate the FWI level and understand wildfire risk conditions.

---

## 🎯 Objective
To build and deploy a **Machine Learning model** that can predict the **FWI value** based on input features like:
- Temperature (°C)
- Relative Humidity (RH %)
- Wind Speed (km/h)
- Rain (mm)
- FFMC (Fine Fuel Moisture Code)
- DMC (Duff Moisture Code)
- ISI (Initial Spread Index)
- Classes (Fire or Not Fire)
- Region (Bejaia or Sidi Bel-abbes)

---

## 🧠 Machine Learning Workflow

1. **Data Collection:**  
   Used the *Algerian Forest Fire Dataset* from the UCI Machine Learning Repository.

2. **Data Preprocessing:**  
   - Handled missing values  
   - Encoded categorical features (Region, Classes)  
   - Normalized numerical features for consistent model performance  

3. **Exploratory Data Analysis (EDA):**  
   - Correlation heatmaps  
   - Distribution plots of weather parameters  
   - Relationship between features and FWI  

4. **Model Training:**  
   Tested various regression models including:
   - Linear Regression  
   - Random Forest Regressor  
   - Decision Tree Regressor  
   - Gradient Boosting  

   The model with the best performance (lowest RMSE, highest R²) was selected for deployment.

5. **Model Deployment (Flask App):**  
   Built a simple **Flask web application** with a user-friendly form where users can enter input values to get the **predicted FWI**.

---

## ⚙️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML, CSS (Styled Form UI) |
| **Backend** | Flask (Python) |
| **ML Model** | Scikit-learn |
| **Data Analysis** | Pandas, NumPy, Matplotlib, Seaborn |
| **Deployment** | Flask App (Local / Render / Heroku) |

---

## 🚀 How to Run Locally

### 1️⃣ Clone this repository
```bash
git clone https://github.com/Aditya5489/FireForestPrediction-MLProject
cd fwi-prediction
