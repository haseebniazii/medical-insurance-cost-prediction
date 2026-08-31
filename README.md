 
<h1 align="center">
   🏥 Medical Insurance Cost Prediction
</h1>
<p align="center">
  🚀 Machine Learning | 📊 Regression | 🌲 Random Forest | 💰 Medical Insurance Cost Prediction
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-Random%20Forest-orange?style=for-the-badge&logo=scikit-learn">
  <img src="https://img.shields.io/badge/Model-Random%20Forest-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/ML-Regression-purple?style=for-the-badge">
</p>

---

## 📌 About The Project

**Medical Insurance Cost Prediction** is a Machine Learning regression project that predicts an individual's **medical insurance charges** based on personal and lifestyle-related information.

The project uses **Random Forest Regression** to learn patterns from historical insurance data and generate predictions for new individuals.

This project covers the complete Machine Learning workflow, including:

* 📂 Data loading
* 🔍 Data exploration
* 🧹 Data cleaning
* 📊 Exploratory Data Analysis
* 📈 Data visualization
* 🚨 Outlier detection
* 🔤 Categorical data encoding
* 🤖 Random Forest Regression
* 📏 Model evaluation
* 🎯 Prediction on new data

---

## 🎯 Project Objective

The main objective of this project is to build a Machine Learning model that can accurately predict **medical insurance costs**.

Given information such as age, BMI, number of children, smoking status, and region, the model predicts the expected insurance charges.

---

## 📊 Dataset

The dataset contains information about individuals and their medical insurance costs.

### Features

| Feature    | Description                   |
| ---------- | ----------------------------- |
| `age`      | Age of the individual         |
| `sex`      | Gender of the individual      |
| `bmi`      | Body Mass Index               |
| `children` | Number of children/dependents |
| `smoker`   | Smoking status                |
| `region`   | Residential region            |
| `charges`  | Medical insurance cost        |

### Target Variable

```text
charges
```

The `charges` column is the target variable that the model learns to predict.

---

## 🛠️ Technologies Used

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-Learn
* 🌲 Random Forest Regressor
* 📓 Jupyter Notebook
* 💾 Joblib / Pickle

---

## 🤖 Machine Learning Model

The main model used in this project is:

### 🌲 Random Forest Regressor

Random Forest is an ensemble Machine Learning algorithm that combines multiple decision trees to produce a more reliable and accurate prediction.

It is particularly useful for regression problems because it can capture:

* Non-linear relationships
* Feature interactions
* Complex patterns in the dataset

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Visualization
   ↓
Outlier Detection
   ↓
Categorical Encoding
   ↓
Train/Test Split
   ↓
Random Forest Regression
   ↓
Model Evaluation
   ↓
Insurance Cost Prediction
```

---

## 📏 Model Evaluation

The Random Forest model is evaluated using standard regression metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the square root of the Mean Squared Error.

### R² Score

Measures how well the model explains the variation in the target variable.

---

## 📈 Results

The final model performance can be found in the Jupyter Notebook.

| Metric   | Score |
| -------- | ----: |
| MAE      |     — |
| MSE      |     — |
| RMSE     |     — |
| R² Score |     — |

> **Note:** Replace the values above with the final Random Forest evaluation results from the notebook.

---

## 🔮 Prediction

After training, the model can be used to predict insurance costs for new individuals.

Example input:

```text
Age
Sex
BMI
Children
Smoker
Region
```

The trained model then returns the predicted medical insurance charge.

---

## 📁 Project Structure

```text
medical-insurance-cost-prediction/
│
├── 📓 medical_insurance_cost_prediction.ipynb
├── 📊 insurance.csv
├── 🤖 model.pkl
├── 📄 README.md
└── 📄 requirements.txt
```

> File names can be adjusted according to the actual files in the repository.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/haseebniazii/medical-insurance-cost-prediction.git
```

Navigate to the project directory:

```bash
cd medical-insurance-cost-prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

## ▶️ How to Run

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
medical_insurance_cost_prediction.ipynb
```

Run the notebook cells step by step to reproduce the analysis, model training, evaluation, and predictions.

---

## 💡 Key Learnings

Through this project, I practiced:

* Data preprocessing
* Exploratory Data Analysis
* Data visualization
* Handling categorical variables
* Outlier detection
* Regression modeling
* Random Forest
* Model evaluation
* Performance analysis
* Saving trained Machine Learning models

---

## 🚀 Future Improvements

Possible improvements include:

* 🔧 Hyperparameter tuning using `GridSearchCV`
* ⚡ Randomized Search optimization
* 📊 Feature importance analysis
* 🌐 Deploying the model using FastAPI
* 🖥️ Building a web interface
* ☁️ Deploying the application online

---

## 👨‍💻 Author

### Haseeb Khan

Computer Science student focused on **Machine Learning, Python, and practical AI projects**.

<p align="center">
  ⭐ If you found this project useful, consider giving the repository a star!
</p>

---

## 📜 License

This project is created for **educational and learning purposes**.
