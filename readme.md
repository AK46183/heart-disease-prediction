# Heart Disease Prediction

Machine Learning project for predicting heart disease** using "Logistic Regression".

## Project Overview

This project predicts the likelihood of heart disease based on patient medical data.
The Logistic Regression model is trained on relevant features to provide accurate predictions and assist in early detection.

## How It Works

1. Input patient data (age, blood pressure, cholesterol, etc.)
2. Preprocess the data using a saved scaler (`scaler.pkl`)
3. Predict the probability of heart disease using the trained model (`Logistic Regression.pkl`)
4. Display the results via the application (`app.py`)

## Repository Structure

| File                      | Description                                |
| ------------------------- | ------------------------------------------ |
| `app.py`                  | Main application script to run predictions |
| `Logistic Regression.pkl` | Trained Logistic Regression model          |
| `scaler.pkl`              | Preprocessing scaler for input data        |
| `heart_columns.pkl`       | Column names used for the model            |
| `README.md`               | Project documentation                      |

## Installation & Usage

1.Clone the repository:

```bash
git clone https://github.com/AK46183/heart-disease-prediction.git
```

2. Navigate to the project folder:

```bash
cd heart-disease-prediction
```

3.Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
python app.py
```

## Future Improvements

* Integrate a web-based interface for easier user interaction
* Add more advanced models like Random Forest or XGBoost for better accuracy
* Include more patient features to improve prediction reliability
