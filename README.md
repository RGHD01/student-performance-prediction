# Student Performance Prediction

## Overview

This project explores factors that influence student academic performance and develops a machine learning model to predict students' final grades. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, visualization, and predictive modeling using Linear Regression.

The objective is to identify the most influential factors affecting academic success and evaluate the ability of machine learning techniques to predict final student performance.

---

## Dataset

The dataset contains demographic, social, and academic information about students, including:

* Age
* Study time
* Absences
* Previous grades (G1, G2)
* Failures
* Family and social factors

### Target Variable

* **G3** – Final Grade

---

## Project Workflow

### 1. Data Preprocessing

* Data loading and inspection
* Handling missing values
* Data cleaning
* Duplicate checking
* Data type validation
* Outlier detection and treatment

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis
* Correlation analysis
* Feature relationship visualization
* Student performance trends

### 3. Feature Selection

Key features used for prediction include:

* G1 (First Period Grade)
* G2 (Second Period Grade)
* Study Time
* Failures
* Absences

### 4. Machine Learning Model

* Linear Regression
* Train/Test Split
* Model Training
* Performance Evaluation

### 5. Model Evaluation

The model performance was evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Actual vs Predicted Grade Comparison

---

## Key Visualizations

### Correlation Heatmap

Shows relationships between numerical features and student performance.

### Actual vs Predicted Grades

Compares model predictions with actual student grades to evaluate prediction accuracy.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---
## Repository Structure

```
student-performance-prediction/
│
├── data/
│   ├── math-raw.csv
│   └── cleaned_student_performance.csv
│
├── images/
│   ├── correlation_heatmap.png
│   └── actual_vs_predicted.png
│
├── notebooks/
│   └── student_performance_prediction.ipynb
│
├── requirements.txt
│
└── README.md
```



---

## Results

The analysis showed that previous academic performance (G1 and G2) is the strongest predictor of the final grade (G3). Study time generally has a positive impact on performance, while failures and absences are associated with lower final grades.

---

## How to Run

1. Download or clone the repository.
2. Install the required libraries:

pip install -r requirements.txt

3. Open the notebook:

jupyter notebook student_performance_prediction.ipynb

---

## Author

**Raghad Alkhateeb**


