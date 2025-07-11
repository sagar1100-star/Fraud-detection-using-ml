# 🕵️‍♂️ Fraud Detection using Machine Learning

This project is a complete **Fraud Detection System** built with **Machine Learning** and a **Flask Web Interface**. It allows users to detect fraudulent transactions using a trained model and view predictions in a user-friendly way.

## 🚀 Features

- Machine Learning model trained to detect fraudulent data.
- Flask-powered web interface for user interaction.
- Upload CSV file and get predictions directly from the browser.
- Pre-trained model stored as `.pkl` file and loaded on runtime.

## 📂 Project Structure


## 🧠 Technologies Used

- Python 3
- Scikit-learn
- Pandas, NumPy
- Flask
- HTML (Jinja2 templates)

## 📊 How the Model Works

The model was trained on transactional data where fraudulent and non-fraudulent transactions were labeled. After training, the model was saved using `joblib` or `pickle` and used in a Flask app to serve predictions in real-time.

## 💻 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/sagar1100-star/Fraud-detection-using-ml.git
cd Fraud-detection-using-ml
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
pip install -r requirements.txt
python app.py


