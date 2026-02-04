# Deep Learning Classification | Adult Income Dataset (UCI)

This project implements an end-to-end Deep Learning pipeline to predict whether an individual earns more than $50K per year using the UCI Adult Census Income Dataset. The model is developed using a Multi-Layer Perceptron (MLP) with TensorFlow and Keras.

## Project Overview
- Loaded and explored the Adult Income Dataset using Pandas
- Performed data preprocessing:
  - Handling missing values
  - One-hot encoding categorical features
  - Feature scaling for numerical columns
- Built and trained a Deep Neural Network (MLP) for binary classification
- Evaluated model performance using accuracy and standard classification metrics
- Generated predictions and compared actual vs predicted results

## Dataset
- Source: UCI Machine Learning Repository
- Target Variable: Income (`<=50K` or `>50K`)

## Technologies Used
- Python
- Pandas, NumPy
- TensorFlow, Keras
- Scikit-learn

## Project Structure
adult-income-deep-learning/
│
├── notebooks/
│ └── Adult_Income_Classification.ipynb
│
├── data/
│ └── adult.csv
│
├── requirements.txt
├── README.md
└── LICENSE

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

