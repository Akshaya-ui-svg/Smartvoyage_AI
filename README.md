# 🌍 Travel Prediction App

An interactive **Machine Learning + Streamlit** web app that predicts travel preferences based on user information such as **age, gender, budget, duration, and travel type**.  

Built with 💻 Python, 🧠 Scikit-learn, and ⚡ Streamlit.

---

## 🧠 Model Overview

The core model used is a **Random Forest Classifier**, trained on travel-related data to understand how various features influence travel preferences.  
All preprocessing steps (scaling and encoding) are saved with **Joblib** for consistent prediction.

**Components:**
- 🧩 `travel_model.pkl` → Trained ML model  
- ⚖️ `scaler.pkl` → StandardScaler for numeric features  
- 🔢 `label_encoder.pkl` → Target encoder  
- 🔠 `label_encoder0.pkl` – `label_encoder8.pkl` → Feature encoders  

---

## 🚀 How to Run the App

### 1️⃣ Clone or Download the Repository
```bash
git clone https://github.com/yourusername/travel-prediction-app.git
cd travel-prediction-app

