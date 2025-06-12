# Brain_stroke_prediction

🧠 Brain Stroke Prediction
A machine learning web app that predicts the likelihood of a brain stroke based on health data such as age, BMI, glucose level, and lifestyle factors.

📌 Features
   1. Predicts stroke likelihood using a trained ML model
   2. User-friendly web interface built with Flask
   3. Accepts key health inputs and gives real-time results

🚀 How to Run
Clone the repo
git clone https://github.com/yourusername/brain-stroke-prediction.git
cd brain-stroke-prediction
Create virtual environment & activate

python -m venv myenv
myenv\Scripts\activate  # On Windows
Install dependencies

pip install -r requirements.txt
Run the app

python app.py
Then open http://127.0.0.1:5000 in your browser.

🧠 Model Details
Trained on a stroke prediction dataset (e.g. Kaggle)
Uses scikit-learn pipeline with encoders and classifiers
Key features: age, hypertension, heart_disease, avg_glucose_level, bmi, etc.
