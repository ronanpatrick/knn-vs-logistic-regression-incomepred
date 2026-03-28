# Income Prediction: Model Comparison (KNN vs. Logistic Regression)

> **Project Objective:** A comparative analysis evaluating the performance, interpretability, and trade-offs between K-Nearest Neighbors and Logistic Regression classifiers on demographic data.

## Project Overview
This repository contains an end-to-end machine learning case study predicting whether an individual's income exceeds $50K/yr based on census data. Rather than just deploying a single algorithm, this project builds two separate models (KNN and Logistic Regression) to directly compare their predictive capabilities and theoretical applications. 

**A full analysis of the findings is available in the included PDF Case Study Report.**

## Dataset
* **Source:** `uciml/adult-census-income` (Fetched programmatically via Kaggle API)
* **Target Variable:** `income` (Binary: >50K or <=50K)

## Repository Structure
* **`KNN_vs_Logistic_Regression_Case_Study.pdf`**: The formal report detailing the comparative analysis, evaluation metrics, and final model recommendations.
* **`Income_Prediction_(KNN).ipynb`**: The data preprocessing and modeling pipeline utilizing the K-Nearest Neighbors algorithm.
* **`Income_Prediction_(Logistic_Regession).ipynb`**: The data preprocessing and modeling pipeline utilizing the Logistic Regression algorithm.

## Tech Stack
* **Language:** Python
* **Data Ingestion:** `kagglehub`
* **Machine Learning:** Scikit-Learn (`KNeighborsClassifier`, `LogisticRegression`)
* **Data Manipulation & Viz:** Pandas, NumPy, Matplotlib

## How to Run the Notebooks

### Run in Cloud (Recommended)
You can view and execute the code instantly in your browser via Google Colab. The dataset will automatically download to your session via the Kaggle API.

* **KNN Model:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronanpatrick/knn-vs-logistic-regression-incomepred/blob/main/Income_Prediction_(KNN).ipynb)

* **Logistic Regression Model:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronanpatrick/knn-vs-logistic-regression-incomepred/blob/main/Income_Prediction_(Logistic_Regession).ipynb)

### Run Locally
1. Clone this repository: `git clone https://github.com/ronanpatrick/knn-vs-logistic-regression-incomepred.git`
2. Install the required libraries: `pip install pandas numpy scikit-learn matplotlib kagglehub`
3. Open either `.ipynb` file in Jupyter Notebook or VS Code and execute the cells.
