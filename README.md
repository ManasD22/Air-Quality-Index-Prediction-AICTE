---

### **Air Quality Index (AQI) Prediction Model**  

This repository contains a **Machine Learning model** that predicts the **Air Quality Index (AQI)** based on various environmental pollutants. The project utilizes **Python, Jupyter Notebook, and Scikit-Learn** to analyze air pollution data and provide AQI predictions.  

## 📌 **Project Overview**  
Air pollution is a major environmental concern affecting public health. This project aims to develop a predictive model that estimates AQI based on pollutant levels such as:  
- **PM2.5** (Particulate Matter <2.5 µm)  
- **PM10** (Particulate Matter <10 µm)  
- **NO₂** (Nitrogen Dioxide)  
- **SO₂** (Sulfur Dioxide)  
- **CO** (Carbon Monoxide)  
- **O₃** (Ozone)  

The model processes **historical air quality data**, applies **machine learning algorithms**, and provides **insights into pollution trends**.  

---

## 🚀 **Features**  
✔️ **Data Preprocessing** – Cleans and handles missing values  
✔️ **Exploratory Data Analysis (EDA)** – Visualizes air pollutant trends  
✔️ **Feature Engineering** – Selects key air quality indicators  
✔️ **Machine Learning Model** – Uses **Linear Regression, Decision Trees, Random Forest, or Neural Networks** for AQI prediction  
✔️ **Model Evaluation** – Measures accuracy using **RMSE, R² Score**  
✔️ **Visualization** – Graphs air pollution trends with **Matplotlib & Seaborn**  

---

## 🛠️ **Technologies Used**  
- **Python** 🐍  
- **Jupyter Notebook** 📒  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-Learn** – Machine Learning models  
- **TensorFlow/Keras (Optional)** – Deep Learning models  

---

## 📂 **Project Structure**  
```
📦 Air-Quality-Index-Prediction-AICTE
│-- 📄 AQI Prediction Model.ipynb  # Jupyter Notebook with the model
│-- 📄 requirements.txt            # Required Python libraries
│-- 📂 dataset/                     # Air quality dataset (CSV)
│-- 📄 README.md                    # Project Documentation
```

---

## 📊 **How to Use the Model**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/ManasD22/Air-Quality-Index-Prediction-AICTE.git
cd Air-Quality-Index-Prediction-AICTE
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**  
```bash
jupyter notebook
```
- Open **`AQI Prediction Model.ipynb`** and run the cells step by step.

---

## 📈 **Results & Insights**  
- The model predicts AQI values with good accuracy.  
- Higher **PM2.5 & PM10** levels significantly affect AQI.  
- Random Forest performed better than Linear Regression in AQI prediction.  

---

## 🏗️ **Future Improvements**  
🔹 Incorporate **Deep Learning (LSTMs/ANNs)** for time-series AQI prediction.  
🔹 Use **real-time API data** for live AQI forecasting.  
🔹 Deploy the model using **Flask/Django** for a web-based AQI predictor.  

---

## 📜 **License**  
This project is **open-source** and available under the **MIT License**.  

---

## 💡 **Contributions & Feedback**  
🙌 Contributions are welcome! If you find any issues or have suggestions, feel free to **open an issue or submit a pull request**.  

💬 Have questions? Reach out via **[GitHub Issues](https://github.com/ManasD22/Air-Quality-Index-Prediction-AICTE/issues)**.  

---
