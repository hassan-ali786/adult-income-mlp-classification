# Deep Learning Classification | Adult Income Dataset (UCI)

An end-to-end deep learning project that predicts whether an individual earns more than $50K per year using the UCI Adult Census Income Dataset.  
The model uses a Multi-Layer Perceptron (MLP) built with **TensorFlow** and **Keras**.

---

## Project Overview

This project implements a complete deep learning workflow:

- Load and explore the Adult Income Dataset using Pandas  
- Perform data preprocessing:  
  - Handle missing values  
  - One-hot encode categorical features  
  - Scale numerical features  
- Build and train a Deep Neural Network (MLP) for binary classification  
- Evaluate model performance using accuracy, precision, recall, and F1-score  
- Generate predictions and compare actual vs predicted outcomes  

---

## Dataset Information

- **Source:** UCI Machine Learning Repository  
- **Target Variable:** Income (`<=50K` or `>50K`)  
- **Features Include:** Age, Workclass, Education, Marital Status, Occupation, Relationship, Race, Sex, Capital Gain, Capital Loss, Hours per week, Native Country  

---

### Features Include:

- Age  
- Workclass  
- Education  
- Marital Status  
- Occupation  
- Relationship  
- Race  
- Sex  
- Capital Gain  
- Capital Loss  
- Hours per week  
- Native Country  

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Project Structure

```bash
adult-income-mlp-classiffication/
├── notebooks/
│   └── Adult_Income_Classification.ipynb
├── data/
│   └── adult.csv
├── requirements.txt
├── README.md
└── LICENSE
```

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/hassan-ali786/adult-income-mlp-classification.git
cd adult-income-mlp-classification

```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/Adult_Income_Classification.ipynb
```

4. Run all cells to reproduce data preprocessing, model training, and evaluation results.

---

## Key Learnings

- Handling categorical and numerical features for deep learning  
- Preprocessing pipelines for MLP models  
- Building, training, and evaluating neural networks with TensorFlow/Keras  
- Interpreting model performance using classification metrics  
- Predicting outcomes on real-world census data  

---

## Future Improvements

- Experiment with additional architectures (more layers, dropout, batch normalization)  
- Hyperparameter tuning (learning rate, epochs, batch size)  
- Implement cross-validation and model checkpoints  
- Deploy as a web application for interactive predictions  
- Add feature importance analysis and visualizations  

---

## Author

**Hassan Ali**  
 Data Scientist & Deep Learning Practitioner  

GitHub: https://github.com/hassan-ali786  

---

⭐ Feel free to fork this repository and explore further improvements!
