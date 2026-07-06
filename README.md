# 💰 Employee Salary Prediction App
 
A simple Streamlit web app that predicts employee salary using a pre-trained
scikit-learn Linear Regression model.
 
## Features
 
- Interactive inputs for Age, Years of Experience, City Tier, Performance
  Score, Number of Skills, and Remote Work status
- One-click salary prediction
- Custom styled UI (green gradient background, orange buttons)
## Requirements
 
- Python 3.8+
- streamlit
- scikit-learn
- joblib
Install dependencies:
 
```bash
pip install streamlit scikit-learn joblib
```
 
## Files
 
- `app.py` — Streamlit app source code
- `salary_model.pkl` — Pre-trained Linear Regression model (scikit-learn)
## Usage
 
Make sure `app.py` and `salary_model.pkl` are in the same directory, then run:
 
```bash
streamlit run app.py
```
 
The app will open in your browser. Enter the employee details and click
**Predict Salary** to see the estimated salary.
 
## Notes
 
- Education level is fixed to **Master's** and Job Role is fixed to
  **ML Engineer** in the current version — these aren't exposed as inputs.
- The model was trained with scikit-learn; if you see a version-mismatch
  warning when loading it, consider retraining or matching your installed
  scikit-learn version to the one used for training.
