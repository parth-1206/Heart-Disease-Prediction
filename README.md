# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Overview

Heart Disease Prediction is a Machine Learning project that predicts the likelihood of heart disease based on various medical attributes of a patient.

This project uses the **K-Nearest Neighbors (KNN)** algorithm to make predictions based on input health-related features. It includes data preprocessing, model training, feature scaling, and an interactive web application developed using Streamlit.

The project demonstrates the application of Machine Learning in healthcare-related predictive analysis.

## 🚀 Features

- Predict the likelihood of heart disease.
- Machine Learning model based on K-Nearest Neighbors (KNN).
- Interactive web interface using Streamlit.
- Data preprocessing and feature scaling.
- Model trained and saved for reuse.
- User-friendly input interface.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Streamlit**
- **Matplotlib**
- **Seaborn**

## 📂 Project Structure

```text
Project1/
│
├── app.py              # Streamlit web application
├── columns.pkl          # Saved feature columns
├── heart.csv           # Dataset
├── KNN_heart.pkl       # Trained KNN model
├── Project2.ipynb      # Model development notebook
├── scaler.pkl          # Saved feature scaler
└── README.md            # Project documentation
```

## 🧠 Machine Learning Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Processing
5. Feature Scaling
6. Model Training using KNN
7. Model Evaluation
8. Model Saving
9. Deployment using Streamlit

## 📊 Algorithm Used

### K-Nearest Neighbors (KNN)

K-Nearest Neighbors is a supervised Machine Learning algorithm used for classification and regression tasks.

In this project, KNN is used to classify patient data based on the similarity of their medical attributes to data points in the training dataset.

The algorithm determines the classification by considering the nearest data points.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Heart-Disease-Prediction
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install pandas numpy scikit-learn streamlit matplotlib seaborn
```

### 6. Run the application

```bash
python -m streamlit run app.py
```

The Streamlit application will open in your browser.

## 📁 Files Description

| File | Description |
|---|---|
| `app.py` | Streamlit application for heart disease prediction |
| `heart.csv` | Dataset used for model development |
| `KNN_heart.pkl` | Saved trained KNN model |
| `scaler.pkl` | Saved scaler for preprocessing input data |
| `columns.pkl` | Saved feature column structure |
| `Project2.ipynb` | Jupyter notebook for analysis and model training |

## 🎯 Objective

The objective of this project is to build a Machine Learning-based application that analyzes medical data and predicts the likelihood of heart disease while learning the practical implementation of data preprocessing, classification, model evaluation and deployment.

## ⚠️ Disclaimer

This project is developed for educational purposes only. Its predictions should not be used as a substitute for professional medical diagnosis or advice.

## 👨‍💻 Author

**Sahitya Parth**