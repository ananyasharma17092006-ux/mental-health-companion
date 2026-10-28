# Mental Health Companion

A web app that predicts a student's mental health score from their
social media and lifestyle habits.

## What it does
- Takes inputs like daily social media hours, sleep, study time,
  physical activity and stress level
- Predicts a mental health score (roughly 3 to 10) with a machine
  learning model
- Served through a FastAPI backend and a simple web page
- - An AI wellness chat companion with safety guardrails

## Dataset
Student Social Media and Mental Health Impact: 5,000 students,
13 columns.

## Tech used
- Python, pandas, scikit-learn (model training)
- FastAPI (backend API)
- HTML, CSS, JavaScript (frontend)

## How to run it
1. Install the libraries:
   pip install fastapi uvicorn pydantic scikit-learn pandas joblib
2. Start the backend:
   uvicorn main:app --reload
3. Open index.html in your browser, fill in the form and click predict.

## Files
- ML_Projectt.ipynb: data cleaning, training and saving the model
- main.py: FastAPI backend
- index.html, style.css, script.js: the website
- Mental_Health_Model.pkl: the trained model

## Note
A learning project, not medical advice.
