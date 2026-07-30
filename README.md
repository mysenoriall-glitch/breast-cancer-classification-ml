# breast-cancer-classification-ml
End-to-end Machine Learning project for Breast Cancer Classification using Python and Scikit-learn.

# 🩺 Breast Cancer Classification Using Machine Learning

**Healthcare Analytics Portfolio – Volume 01**

An end-to-end machine learning project that classifies breast tumors as **benign** or **malignant** using the Breast Cancer Wisconsin dataset. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model development, evaluation, and deployment preparation.

---

## 📋 Project Overview

Breast cancer is one of the most common cancers worldwide. Early detection and accurate diagnosis are essential for improving patient outcomes.

This project applies supervised machine learning techniques to predict whether a breast tumor is benign or malignant based on diagnostic measurements.

The project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature scaling
* Model development
* Model evaluation
* Best model selection
* Model serialization using Joblib

---

## 🎯 Objectives

* Analyze and understand the Breast Cancer Wisconsin dataset.
* Preprocess and prepare the data for machine learning.
* Train and compare multiple classification algorithms.
* Evaluate models using standard performance metrics.
* Select the best-performing model.
* Save the trained model for future deployment.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook / Google Colab
* Git & GitHub

---

## 📊 Dataset Information

**Dataset:** Breast Cancer Wisconsin Dataset

**Features:** 30 numerical features

**Target Classes:**

* Benign (0)
* Malignant (1)

The dataset contains measurements computed from digitized images of breast mass samples.

---

## 🔄 Machine Learning Workflow

```text
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
(Logistic Regression,
Decision Tree,
KNN)
   │
   ▼
Model Evaluation
   │
   ▼
Best Model Selection
   │
   ▼
Model Serialization
```

---

## 🤖 Models Implemented

The following machine learning algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Classification Report

---

## 🏆 Best Model

After comparing the performance of all models, **K-Nearest Neighbors (KNN)** achieved the best overall performance and was selected as the final model.

---

## 📁 Project Structure

```text
breast-cancer-classification-ml/

├── README.md
├── LICENSE
├── requirements.txt
│
├── data/
│   └── breast_cancer.csv
│
├── notebooks/
│   └── Breast_Cancer_Classification.ipynb
│
├── models/
│   └── breast_cancer_knn.joblib
│
├── images/
│   ├── workflow.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix_knn.png
│   └── model_comparison.png
│
└── reports/
    └── HAP-001_Report.pdf
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/breast-cancer-classification-ml.git
```

Move into the project directory:

```bash
cd breast-cancer-classification-ml
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📷 Project Visualizations

The repository includes:

* Correlation heatmap
* Feature distributions
* Confusion matrices
* Model comparison charts
* Workflow diagram

---

## ⚠️ Disclaimer

This project is intended for educational and portfolio purposes only. It is not designed for clinical use and should not be used for medical diagnosis or treatment decisions.

---

## 👨‍💻 Author

**[Prosenjit Ghosh Dastidar]**

Healthcare Analytics Professional

Skills:

* Healthcare Analytics
* Python
* SQL
* Power BI
* Machine Learning
* Data Visualization
* Artificial Intelligence

---

## 📄 License

This project is licensed under the MIT License.
