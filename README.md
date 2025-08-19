# Heart_Disease_Prediction

This project aims to build a **machine learning model** to predict the presence of heart disease using the **UCI Heart Disease dataset**. 
The model is trained, evaluated, and then deployed using **Streamlit** as a simple web application.  

---

## 📂 Project Structure
├── heart_disease_prediction.ipynb # Jupyter Notebook for EDA & model training
├── heart_disease_uci.csv # Dataset (UCI Heart Disease)
├── final_pipe.sav # Trained model (saved pipeline)
└── app.py # Streamlit app for deployment

---

## 📊 Dataset
The dataset used is **Heart Disease UCI dataset**.  
It contains clinical features such as age, sex, blood pressure, cholesterol, and other health indicators to predict the presence of heart disease.  

---

🚀 Usage
1. Run Jupyter Notebook (for EDA & training)
bash
Copy
Edit
jupyter notebook heart_disease_prediction.ipynb
2. Run Streamlit App
bash
Copy
Edit
streamlit run app.py
This will open the app in your browser at http://localhost:8501.

📦 Model
The final trained model is saved as final_pipe.sav (using Scikit-learn pipeline).

The model is loaded in app.py to provide real-time predictions via a web interface.

