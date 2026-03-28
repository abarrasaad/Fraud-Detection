# Fraud Detection App (Streamlit)

## Project Overview

This project focuses on building a **fraud detection system** using a real-world fraud detection dataset. The goal is to analyze the dataset, build a machine learning model capable of predicting fraudulent transactions, and deploy it using **Streamlit** for interactive use.

The application allows users to input transaction information and instantly get a prediction of whether the transaction is **fraudulent** or **legitimate**.

---

## Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Machine Learning model for fraud prediction
* Model evaluation (accuracy, precision, recall, etc.)
* Interactive web application built with Streamlit
* Real-time fraud prediction from user input

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Streamlit

---

## Dataset

The project is based on a large fraud detection dataset.

⚠️ The dataset is **not included in this repository** because its size is approximately **500 MB**, which exceeds GitHub's upload limits.

If you want to run the project locally, you can:

1. Download the dataset from the original source (https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset).
2. Place the dataset file inside the project folder.
3. Update the dataset path in the notebook or Python script if needed.

---

## Project Structure

```bash
Fraud-Detection-Project/
│
├── fraud_detection.py            # Main Python script for the project
├── fraud-detection.ipynb         # Notebook used for data analysis and model training
├── fraud_detection_pipeline.pkl  # Saved trained model (pipeline)
└── README.md                     # Project documentation
```

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/abarrasaad/Fraud-Detection.git
cd Fraud-Detection
```

### 2. Install the required libraries


### 3. Run the Streamlit app

```bash
streamlit run app.py
```

---

## How the Model Works

The model was trained using a fraud detection dataset that contains transaction-related features. After preprocessing the data and handling missing values, a machine learning model was trained to classify transactions into two categories:

* Fraudulent transaction
* Legitimate transaction

The trained model is saved as a `.pkl` file and loaded directly inside the Streamlit application for real-time predictions.

---

