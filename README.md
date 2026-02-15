# Energy Consumption Prediction System
Machine Learning Project
By Shivam kumar , sec- F
reg no - 2427030210

This project focuses on predicting household energy consumption using machine
learning techniques. A Random Forest Regressor is trained on the UCI Energy
Efficiency dataset to estimate energy usage based on indoor and outdoor
environmental conditions.

---

## 📌 Project Overview
Energy consumption prediction is an important problem in smart home systems and
energy management. This project applies a supervised machine learning approach
to predict appliance energy consumption using temperature, humidity, and
weather-related features.

---

## 🧠 Algorithm Used
- Random Forest Regression

---

## 🗂 Dataset
- Source: UCI Machine Learning Repository  
- Dataset: Energy Efficiency Dataset  
- Target Variable: Appliances (Energy Consumption)  
- Unit Conversion: Watt-hours (Wh) → Kilowatt-hours (kWh)

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/energy-consumption-prediction.git
cd energy-consumption-prediction
2. Install Dependencies
pip install pandas numpy scikit-learn matplotlib
3. Run the Model
python energy_prediction.py
📊 Output
After running the program, the following outputs are generated:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Scatter plot comparing actual and predicted energy consumption

Energy consumption prediction for new input data

Sample Results
Mean Absolute Error (MAE): 0.03 kWh

Mean Squared Error (MSE): ~0.00

R² Score: 0.54

Predicted Energy Consumption (New Data): 0.31 kWh

📈 Visualization
The scatter plot titled “Actual vs Predicted Energy Consumption” shows a
positive correlation between actual and predicted values, indicating that the
model captures the overall trend of energy usage despite real-world variability.

⚙️ Working Methodology
Load dataset from the UCI repository

Remove irrelevant features and preprocess data

Split the dataset into training and testing sets

Train a Random Forest Regressor

Evaluate the model using regression metrics

Predict energy consumption for new unseen inputs

🛠 Technologies Used
Python

Pandas

NumPy

scikit-learn

Matplotlib

🎯 Applications
Smart home energy monitoring

Energy usage forecasting

Consumption pattern analysis

⚠️ Limitations
Model performance depends on dataset quality

Moderate R² score due to variability in household behavior

Designed for academic and educational purposes

🚀 Future Scope
Hyperparameter tuning to improve accuracy

Feature selection and optimization

Comparison with other regression models

Time-series based energy forecasting

👨‍💻 About
Project Type: Machine Learning Academic Project
Dataset: UCI Energy Efficiency Dataset

📄 License
This project is intended only for educational purposes.
