# 🚗 Car Price Predictor
A Machine Learning web application built using Flask that predicts the selling price of a used car based on company, model, year, fuel type, and kilometers driven.
This project demonstrates an end-to-end ML pipeline — from data preprocessing and model training to deployment using Flask.

<img width="1912" height="1028" alt="Car_Price_Predictor" src="https://github.com/user-attachments/assets/b2d94c39-8b01-49e4-91cf-e00932be58d9" />

## 📌 Features
- Predicts used car price using Linear Regression
- Interactive Bootstrap UI
- No page reload during prediction (AJAX integration)
- Dynamic dropdowns for car details
- Clean and simple web interface

## 🛠 Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript (AJAX)
### Backend
- Python
- Flask
### Machine Learning
- Scikit-learn
- Pandas
- Numpy

## ⚙️ Installation & Setup
### 1️⃣ Clone the repository
- git clone https://github.com/Mayank312003/car-price-predictor-python-machine-learning.git
- cd car-price-predictor-python-machine-learning
### 2️⃣ Install dependencies
pip install flask pandas numpy scikit-learn
### 3️⃣ Run the application
python application.py
Open in browser:
http://127.0.0.1:5000/

## 📊 Model Information
- Algorithm: Linear Regression
- Encoding: One Hot Encoding
- Evaluation Metric: R² Score
- Trained on cleaned used car dataset

## 🧠 How It Works
1. User selects:
- Company
- Model
- Year
- Fuel Type
- KM Driven
2. Data is sent to Flask backend using AJAX.
3. The trained ML model predicts the price.
4. The estimated price is displayed instantly on the same page.

## 🚀 Future Improvements
- Deploy on Render / Railway / AWS
- Add model comparison (Ridge, Lasso)
- Improve UI design
- Add dynamic model filtering based on company
- Add prediction confidence interval

## 📷 Demo
### Demo1:
<img width="1917" height="1025" alt="demo1" src="https://github.com/user-attachments/assets/8fbbcf61-5d74-4a5b-85d6-adbdf60a9c22" />

### Demo2:
<img width="1917" height="1032" alt="demo2" src="https://github.com/user-attachments/assets/9f16396c-5fe4-4799-a701-167d313fc2cf" />

## 👨‍💻 Author
Mayank Yadav.
Aspiring Data Analyst / Data Scientist.

### ⭐ If you found this useful
Give this repo a star.
