# 🦠 AI-Based COVID Detection System

This is a multi-component AI project developed during my internship. It integrates **Computer Vision** and **Data Analysis** to assist in early detection and understanding of COVID-19. The entire system runs as a simple and interactive **Streamlit web application**.

---

## 📌 Project Features

### 1. 🖼️ Chest X-ray Classifier
- Upload a chest X-ray image.
- Predicts whether the X-ray shows signs of:
  - **COVID**
  - **Normal**
  - **Viral Pneumonia**
- Powered by a deep learning model (`covid_xray_model.keras`) built using TensorFlow/Keras.

### 2. 📊 WHO COVID-19 Global Data Analysis
- Uses official WHO dataset (`WHO-COVID-19-global-data.csv`)
- Visualizes:
  - Top 10 countries with highest total reported cases
  - Daily new cases
  - Cumulative case trends by country
  - Raw data display for selected country

---
📦 **Note:** The model file (`covid_xray_model.keras`) is too large for GitHub.

➡️ Please download it from the link below and place it inside the project folder:

🔗 [Download COVID X-ray Model (.keras)](https://drive.google.com/file/d/1CZ0Saujk9J6DfnZlOvdAp-EakWuasWfE/view?usp=sharing)
