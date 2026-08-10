# CodeAlpha_IrisClassification
Iris Flower Classification using Machine Learning
# 🌸 Iris Flower Classification Using Machine Learning

## CodeAlpha Data Science Internship — Task 1

### 📌 Project Overview

This project focuses on classifying Iris flowers into three different species using machine learning techniques.

The classification is based on four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The three species included in the dataset are:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## 🎯 Objective

The main objective of this project is to develop and evaluate machine learning classification models that can accurately predict the species of an Iris flower based on its physical measurements.

---

## 📊 Dataset

The dataset contains **150 Iris flower samples**.

Each species contains 50 samples.

### Features

| Feature | Description |
|---|---|
| SepalLengthCm | Length of the sepal in centimeters |
| SepalWidthCm | Width of the sepal in centimeters |
| PetalLengthCm | Length of the petal in centimeters |
| PetalWidthCm | Width of the petal in centimeters |

### Target

`Species`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

---

## 🔍 Project Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Visualization
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Comparison
10. Prediction

---

## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors

### Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| Decision Tree | 93.33% |
| Random Forest | 90.00% |
| **K-Nearest Neighbors** | **100.00%** |

Based on the test results, **K-Nearest Neighbors achieved the highest accuracy of 100%** on the selected test split.

---

## 📈 Exploratory Data Analysis

The project includes visualizations such as:

- Species distribution
- Sepal length vs. sepal width
- Petal length vs. petal width
- Petal length distribution by species
- Confusion matrix
- Model accuracy comparison

The analysis showed that petal measurements provide strong separation between the three Iris species.

---

## 🧪 Sample Prediction

The final KNN model was tested using a new flower with the following measurements:

- Sepal Length: 5.1 cm
- Sepal Width: 3.5 cm
- Petal Length: 1.4 cm
- Petal Width: 0.2 cm

### Prediction

**Iris-setosa**

---

## 📁 Project Files

```text
CodeAlpha_IrisClassification/
│
├── Iris.csv
├── Iris_Classification.ipynb
├── README.md
└── .gitignore
