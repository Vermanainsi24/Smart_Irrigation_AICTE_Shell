# 🌱 Smart Irrigation using Soil Moisture and Weather Data

## 📌 Problem Statement
Traditional irrigation systems often rely on fixed schedules or manual monitoring, which can lead to water wastage or under-irrigation. With increasing water scarcity, there is a need for a **smart irrigation system** that optimizes water usage based on **soil moisture levels and weather conditions**.

---

## 🎯 Learning Objectives
- **Understand IoT in Agriculture** – Learn how IoT devices and sensors can improve farming efficiency.  
- **Work with Sensors** – Utilize soil moisture sensors and weather data APIs for real-time monitoring.  
- **Data Processing** – Analyze data to make intelligent irrigation decisions.  
- **Automation** – Implement automated irrigation to conserve water.  
- **UI Development** – Create an interactive Streamlit dashboard for data visualization.  

---

## ⚙️ Tools & Technologies Used
- **Programming Language:** Python  
- **Framework:** Streamlit (for UI)  
- **IoT Sensors:** Soil Moisture Sensor, DHT Sensor  
- **Data Source:** Weather API (for rainfall and temperature)  
- **Database:** Firebase / Local storage for sensor data  
- **Libraries:** Pandas, Matplotlib, NumPy, Requests  

---

## 🔎 Methodology
1. **Data Collection**  
   - Gather soil moisture data using sensors.  
   - Fetch weather data (temperature, rainfall prediction) from APIs.  

2. **Data Analysis**  
   - Process soil moisture values and compare with threshold.  
   - Integrate weather predictions to avoid unnecessary irrigation.  

3. **Decision Making**  
   - If soil moisture is below threshold and no rainfall is predicted, trigger irrigation.  

4. **Visualization**  
   - Display real-time sensor and weather data in Streamlit dashboard.  
   - Show irrigation status with interactive UI.  

---

## 💡 Solution
- Monitors **soil moisture in real-time**.  
- Integrates **weather forecast data** to reduce unnecessary watering.  
- Provides a **dashboard for visualization** of data and irrigation status.  
- Enables **automated irrigation** based on intelligent decision-making.  
- Helps farmers **conserve water** and improve crop yield.  

---

## 📥 Inputs
- Soil moisture sensor readings  
- Weather data (temperature, humidity, rainfall)  
- Threshold values for soil moisture  

---

## 📤 Outputs
- Real-time soil moisture percentage  
- Weather conditions (rainfall prediction, temperature)  
- Irrigation ON/OFF status  

---

## ✅ Conclusion
The Smart Irrigation system effectively reduces water wastage by combining **soil moisture data and weather forecasts**. It helps in making intelligent irrigation decisions, ensuring crops get adequate water while conserving resources.

---

## 🚀 Future Objectives
- Integrate **AI/ML models** to predict irrigation needs.  
- Add **mobile notifications** for farmers.  
- Support for **multiple crop types** with different water requirements.  
- Integration with **solar-powered pumps** for sustainability.  
- Cloud-based storage for long-term analysis.  

---
## 📂 Project Structure
```
Smart_Irrigation/
│── Farm_Irrigation_System.pkl # Trained Machine Learning model (saved with Joblib)
│── Irrigation_System.ipynb # Jupyter Notebook for model training & analysis
│── irrigation_machine.csv # Dataset used for training/testing
│── app.py # Streamlit app for sprinkler prediction UI
│── README.md # Project documentation
```

## 🚀 How to Run

1. **Clone the repository**
   ```
   git clone https://github.com/Vermanainsi24/Smart_Irrigation_AICTE_Shell.git
   cd your-repo-name
   ````
2.**Run the Streamlit app**
```
   streamlit run app.py
```


