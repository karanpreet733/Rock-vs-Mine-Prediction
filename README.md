# Rock vs Mine Prediction 🪨💣

## Overview
This repository contains a machine learning project that predicts whether an underwater object is a Rock or a Mine based on sonar data. The classification is performed using a Logistic Regression model built with Python[cite: 1].

## Dataset
* **Data Source:** Sonar dataset containing 208 instances[cite: 1].
* **Features:** 60 numerical features representing energy returns at various sonar frequencies[cite: 1].
* **Labels:** 
  * `R` for Rock[cite: 1].
  * `M` for Mine[cite: 1].

## Tech Stack
* **Language:** Python[cite: 1].
* **Environment:** Jupyter Notebook[cite: 1].
* **Libraries:** 
  * `NumPy` & `Pandas` for data manipulation[cite: 1].
  * `Scikit-Learn` for model building and evaluation[cite: 1].

## Model & Performance
The dataset was split using a 90/10 train-test ratio, stratified to maintain an even class balance across the sets[cite: 1]. 
* **Algorithm:** Logistic Regression[cite: 1].
* **Training Data Accuracy:** ~83.4%[cite: 1].
* **Testing Data Accuracy:** ~76.1%[cite: 1].

## How to Run
1. Clone this repository to your local machine.
2. Ensure you have Python installed along with `numpy`, `pandas`, and `scikit-learn`.
3. Verify that the dataset (`Copy of sonar data.csv`) is placed in the exact same directory as the Jupyter Notebook.
4. Open the `Rock vs Mine Prediction.ipynb` file in your preferred environment (e.g., VS Code or JupyterLab) and run the cells sequentially.
