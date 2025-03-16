#Brain Stroke Prediction

This is a Flask-based web application that preze user input and provide predictions.dicts the likelihood of a person having a stroke based on medical and lifestyle factors. The system uses a Machine Learning model trained with Scikit-Learn to analy

🚀 Features

User-friendly Web Interface: Enter medical and lifestyle details in a simple form.

Machine Learning Model: Uses a trained logistic regression model for stroke prediction.

Data Preprocessing: Encodes categorical variables and scales numerical features before making predictions.

Flask Backend: Handles user input, processes data, and serves the prediction.


📂 Project Structure


📁 Brain_Stroke_Prediction
│── app.py        # Flask application

│── model.joblib             # Pre-trained machine learning model

│── templates/               # HTML templates for web UI

│   ├── index.html           # Input form page

│   ├── result.html          # Prediction result page

│── static/                  # CSS, JS, and images (if needed)

│── train.csv                # Dataset used for training

│── test.csv                 # Dataset used for testing

│── Stroke Prediction.ipynb  # Jupyter Notebook with model training

│── README.md                # Project documentation



📊 Dataset


The model is trained on a stroke prediction dataset containing features such as:


Age
Hypertension (Yes/No)
Heart Disease (Yes/No)
Marital Status
Work Type
Residence Type
Average Glucose Level
BMI (Body Mass Index)
Smoking Status


🛠 Installation




Clone the repository:


git clone https://github.com/Rachana-07/Brain_stroke_Prediction-using-Flask-ML.git
cd Brain_Stroke_Prediction






Run the Flask app:


python app.py



The application will start at http://127.0.0.1:5000/




🔍 Usage


Open http://127.0.0.1:5000/ in your browser.
Enter details like age, medical history, and lifestyle factors.
Click "Predict" to get the result.
The system will display "Detected" or "Not Detected" based on the prediction.


🤖 Model Details


The ML model used is a Logistic Regression classifier, trained using the dataset. The preprocessing steps include:


One-Hot Encoding for categorical features
Feature Scaling for numerical variables
Data Cleaning to handle missing values


🛠 Technologies Used


Python
Flask (for the web app)
Pandas (for data handling)
Scikit-Learn (for ML model)
Joblib (for saving/loading models)
HTML & CSS (for UI)


📌 Future Improvements


Improve UI with Bootstrap or React.js.
Deploy the model to Heroku or AWS.
Enhance prediction accuracy with Deep Learning models.






🚀 Developed for better stroke risk prediction using Machine Learning!
