# Salary Estimation Using K-Nearest Neighbors (KNN)

## Project Overview
This Machine Learning project predicts whether an employee's salary is greater than 50K or less than/equal to 50K using the K-Nearest Neighbors (KNN) algorithm.

## Dataset Features

- Age
- Education Number
- Capital Gain
- Hours Per Week

### Target Variable
- <=50K → 0
- >50K → 1

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Google Colab

## Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing
4. Convert Salary Labels to Binary Values
5. Split Dataset into Training and Testing Sets
6. Feature Scaling using StandardScaler
7. Find Best K Value
8. Train KNN Model
9. Predict Employee Salary
10. Evaluate Model using Confusion Matrix and Accuracy Score

## Algorithm Used

### K-Nearest Neighbors (KNN)

KNN predicts the salary category by finding the nearest similar employees in the dataset and assigning the majority class.

## Project Structure

```
Salary-Estimation-Using-KNN/
│
├── salary.csv
├── Day4_SalaryEstimation_K_NN.ipynb
├── README.md
└── requirements.txt
```

## Installation

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Run Project

```bash
jupyter notebook
```

Open:

```text
Day4_SalaryEstimation_K_NN.ipynb
```

## Model Evaluation

The model is evaluated using:

- Confusion Matrix
- Accuracy Score

## Sample Prediction

Input:

- Age = 35
- Education = 13
- Capital Gain = 0
- Hours Per Week = 40

Output:

```text
Employee might get Salary above 50K
```

## Author

Vaishnavi

This project was implemented during my Machine Learning training. The project was provided by my teacher for learning purposes, and I completed it independently to practice KNN, data preprocessing, model training, and prediction techniques.
