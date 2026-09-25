# Heart Disease Classification

## Project Overview

This project uses Machine Learning to predict whether a patient is at risk of heart disease based on medical and demographic information.

The goal is to demonstrate the complete Machine Learning workflow:

* Data Collection
* Data Exploration
* Data Cleaning
* Feature Engineering
* Model Training
* Model Evaluation
* Prediction

## Dataset

The dataset is stored in `data.csv`.

Example features:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Maximum Heart Rate
* Exercise-Induced Angina

Target Variable:

* Heart Disease (0 = No, 1 = Yes)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

## Project Structure

Heart Disease Classification/

├── data.csv

├── Heart Disease.py

├── README.md

## Machine Learning Process

1. Load dataset using Pandas
2. Explore and clean data
3. Split data into training and testing datasets
4. Train a Machine Learning model
5. Evaluate model accuracy
6. Predict heart disease risk

## How to Run

Activate virtual environment:

```bash
.\.env\Scripts\activate
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib
```

Run the program:

```bash
python "Heart Disease.py"
```

## Sample Output

Model Accuracy: 85%

Prediction: Heart Disease Detected

## Future Improvements

* Hyperparameter tuning
* Additional ML algorithms
* Feature importance analysis
* Model deployment using Flask or Streamlit
* Cloud deployment on AWS

## Author

Amadou Sidibe

Aspiring AI/ML Technical Program Manager
