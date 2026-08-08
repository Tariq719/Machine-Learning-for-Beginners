# Machine Learning for Beginners with Python

A complete beginner-friendly Machine Learning project developed using **Python** and **Scikit-learn**. This repository demonstrates the complete Machine Learning workflow, starting from raw data and ending with trained Machine Learning models.

The project has been designed primarily for students, beginners, and educators who want to understand the practical implementation of Machine Learning through real-world examples.

---

## Project Objectives

This project aims to help learners understand how to:

- Load and explore datasets
- Clean and prepare data
- Perform Exploratory Data Analysis (EDA)
- Apply Feature Engineering
- Encode categorical features
- Scale numerical features
- Split data into training and testing sets
- Train Machine Learning models
- Make predictions
- Evaluate model performance
- Save and reuse trained models

---

## Project Structure

```text
Machine-Learning-for-Beginners
│
├── notebooks
├── datasets
├── models
├── images
└── book
```

---

## Jupyter Notebooks

| Notebook | Description |
|---|---|
| 1-Python | Python fundamentals |
| 2-NumPy | Numerical computing with NumPy |
| 3-Basic Pandas | Data manipulation using Pandas |
| 4-Data Cleaning & Preparation | Data preprocessing techniques |
| 5-Data Visualization | Data visualization using Matplotlib & Seaborn |
| 6-Exploratory Data Analysis | Exploratory Data Analysis (EDA) |
| 7-Feature Relationship & Correlation Analysis | Correlation and feature analysis |
| 8-Feature Engineering | Encoding, scaling and feature preparation |
| 9-Machine Theory | Introduction to Machine Learning concepts |
| 10.1-Linear Regression | Regression model implementation |
| 10.2-Logistic Regression | Classification model implementation |

---

## Dataset

This repository includes a custom educational dataset.

### Original Dataset

**ITAR_Student_Performance_Dataset_v1.0.csv**

### Cleaned Dataset

**student_performance_cleaned.csv**

The dataset contains information related to student academic performance and is used throughout the notebooks to demonstrate the complete Machine Learning workflow.

---

## Machine Learning Algorithms

This project implements:

- Linear Regression
- Logistic Regression

---

## Machine Learning Workflow

```text
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Prediction
      │
      ▼
Model Evaluation
      │
      ▼
Save Model
```

---

# Model Performance

## Linear Regression

| Metric | Score |
|---|---:|
| R² Score | **0.083** |
| Mean Absolute Error (MAE) | **5.062** |
| Mean Squared Error (MSE) | **36.615** |
| Root Mean Squared Error (RMSE) | **6.051** |

The model achieved an **R² score of 0.083**, indicating that it explains a relatively small portion of the variation in the target variable.

## Logistic Regression

The Logistic Regression model was evaluated using accuracy, precision, recall, F1-score, and class-wise performance.

### Classification Report

| Class / Average | Precision | Recall | F1-Score | Support |
|---|---:|---:|---:|---:|
| Class 0 | **0.71** | **0.59** | **0.65** | 17 |
| Class 1 | **0.53** | **0.67** | **0.59** | 12 |
| **Accuracy** | — | — | **0.62** | **29** |
| **Macro Average** | **0.62** | **0.63** | **0.62** | **29** |
| **Weighted Average** | **0.64** | **0.62** | **0.62** | **29** |

### Overall Performance

| Metric | Score |
|---|---:|
| **Accuracy** | **62%** |
| **Macro Precision** | **62%** |
| **Macro Recall** | **63%** |
| **Macro F1-Score** | **62%** |
| **Weighted Precision** | **64%** |
| **Weighted Recall** | **62%** |
| **Weighted F1-Score** | **62%** |

### Class-wise Performance

| Class | Precision | Recall | F1-Score | Support |
|---|---:|---:|---:|---:|
| Class 0 | **71%** | **59%** | **65%** | 17 |
| Class 1 | **53%** | **67%** | **59%** | 12 |

### Logistic Regression Interpretation

- Accuracy: **62%**
- Class 0 precision: **71%**
- Class 0 recall: **59%**
- Class 0 F1-score: **65%**
- Class 1 precision: **53%**
- Class 1 recall: **67%**
- Class 1 F1-score: **59%**
- Macro-average F1-score: **62%**
- Weighted-average precision: **64%**
- Weighted-average recall: **62%**
- Weighted-average F1-score: **62%**

---

## Model Summary

| Model | Task | Evaluation Metrics |
|---|---|---|
| Linear Regression | Regression | R², MAE, MSE, RMSE |
| Logistic Regression | Classification | Accuracy, Precision, Recall, F1-Score |

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Trained Models

The repository includes trained Machine Learning models:

- `linear_regression_model.pkl`
- `logistic_regression_model.pkl`

These models can be loaded using the **Joblib** library without retraining.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Tariq719/Machine-Learning-for-Beginners.git
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Who is this Project For?

This project is suitable for:

- Students
- Beginners
- Data Analysts
- Aspiring Data Scientists
- Educators
- Machine Learning Enthusiasts

---

## Future Improvements

Future versions of this project will include:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- K-Means Clustering
- Deep Learning

---

## Author

**Tariq Nawaz**

IT All-Rounders Computer Academy

Pakistan

---

## License

This project is released under the **MIT License**.

---

## ⭐ Support

If you find this project helpful, please consider giving it a ⭐ on GitHub.

**Happy Learning! 🚀**
