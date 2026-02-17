# 🍭 Diabetes Prediction Web App

This project is a beginner-friendly machine learning web application that predicts a patient’s health risk based on medical input parameters such as glucose level, BMI, age, and blood pressure.
The system uses a trained classification model and provides real-time predictions through an interactive web interface.

---

## 🚀 Project Overview

This lightweight web app allows users to input simple health metrics and instantly receive a diabetes prediction (positive/negative). Built with Streamlit, it features a clean interface and loads a pre-trained model for fast inference.

---

## 💻 Tech Stack

- **Python**
- **scikit-learn** – For training and serving the prediction model
- **Streamlit** – For the interactive web interface
- **Pickle** – To serialize the trained model (`.sav`)
- **NumPy**, **Pandas** – For data handling and preprocessing

---

## 📄 What's Inside

- `app.py`  
  The main Streamlit application. Loads the model, displays the form, runs predictions.

- `diabetes_model.sav`  
  A pre-trained classification model (serialized via Pickle).

- `requirements.txt`  
  Contains dependencies:
  ```
  streamlit
  scikit-learn
  pandas
  numpy
  ```

- `README.md`  
  (You’re here!) Project overview and instructions.

---

## 🧠 How It Works

1. Launches a web interface using Streamlit.
2. User enters health metrics (e.g., pregnancies, glucose, BMI).
3. On form submission, the app loads the pre-trained model.
4. The model processes the input and returns a prediction: **“Diabetic”** or **“Non-diabetic”**.

---

## 📦 Installation & Run Locally

## 📦 Installation & Run Locally

1. Clone the repository:

git clone YOUR_GITHUB_REPO_LINK

cd YOUR_PROJECT_FOLDER_NAME

2. Install dependencies:

pip install -r requirements.txt

3. Run the application:

python -m streamlit run app.py

4. Open the local URL shown in the terminal (usually http://localhost:8501).

---

## ✅ Usage Example

- **Pregnancies**: 2  
- **Glucose**: 120  
- **Blood Pressure**: 70  
- **BMI**: 25  

Click **Predict** → See the result: **Diabetic** or **Non-diabetic**

---

## 🙋‍♂️ Author

**Ayush Shukla**  
Data Scientist & ML Enthusiast  
📬 urayushshukla@gmail.com
