# 🧠Brain_stroke_prediction

A machine learning web app that predicts the likelihood of a brain stroke based on health data such as age, BMI, glucose level, and lifestyle factors.

<img width="1911" height="935" alt="image" src="https://github.com/user-attachments/assets/9d6b1494-98b3-48d3-b86b-8c3ccd2edadd" />


## 📌 Features
   1. Predicts stroke likelihood using a trained ML model
   2. User-friendly web interface built with Flask
   3. Accepts key health inputs and gives real-time results

## 🚀 How to Run
### 1. Clone the repo
```bash
git clone https://github.com/yourusername/brain-stroke-prediction.git
```
### 2. Navigate to this directory
``` bash
cd brain-stroke-prediction
```
### 3. Create a virtual machine
Create virtual environment & activate
```bash
python -m venv myenv
myenv\Scripts\activate  # On Windows
Install dependencies
```
### 4. Download the requirements.txt and run the app
```bash
pip install -r requirements.txt
Run the app
python app.py
```
Then open http://127.0.0.1:5000 in your browser.

## 🧠 Model Details
```bash
Trained on a stroke prediction dataset (e.g. Kaggle)
Uses scikit-learn pipeline with encoders and classifiers
Key features: age, hypertension, heart_disease, avg_glucose_level, bmi, etc.
```
