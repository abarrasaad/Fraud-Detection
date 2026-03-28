# Fraud Detection App

## Project Overview

This project focuses on building a fraud detection system using a real-world fraud detection dataset. The goal is to analyze the dataset, build a machine learning model to predict fraudulent transactions, and deploy it using Streamlit so it can be used interactively.
The application allows users to input transaction information and instantly get a prediction of whether the transaction is fraudulent or legitimate.

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning model for fraud prediction
- Model evaluation (accuracy, precision, recall, etc.)
- Interactive web application built with Streamlit
- Real-time fraud prediction from user input

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Streamlit

## Dataset

The project is based on a large fraud detection dataset.

⚠️ The dataset is not included in this repository because its size is approximately 500 MB, which exceeds GitHub's upload limits.

If you want to run the project locally, you can:

1. Download the dataset from the original source (https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset)
2. Place the dataset file inside the project folder.
3. Update the dataset path in the notebook or Python script if needed.

## Project Structure

Fraud-Detection/
│
├── fraud_detection.py                # Streamlit application
├── fraud-detection.ipynb             # Data analysis and model training
├── fraud_detection_pipeline.pkl      # Trained machine learning model 
└── README.md                         # Project documentation
