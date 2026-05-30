<div align="center">
  
  <h1>💎 Gemstone Price Prediction</h1>
  <p><em>End-to-End Machine Learning Regression Pipeline for Accurate Price Estimation</em></p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg" alt="Python Version">
    <img src="https://img.shields.io/badge/Task-Regression-orange.svg" alt="Task: Regression">
    <img src="https://img.shields.io/badge/Status-Completed-success.svg" alt="Status">
  </p>
</div>

---

## 📖 Overview

This repository contains an end-to-end Machine Learning project designed to predict the price of gemstones based on their physical attributes (such as carat, cut, color, clarity, and dimensions). The project walks through the entire data science lifecycle: from thorough Exploratory Data Analysis (EDA) and robust feature engineering to the training, evaluation, and deployment-readiness of regression models.

## ✨ Key Features

- **Comprehensive EDA:** In-depth statistical analysis and visualizations to understand feature distributions and correlations.
- **Robust Data Preprocessing:** Automated pipelines for handling missing values, encoding categorical variables (cut, color, clarity), and feature scaling.
- **Advanced Regression Modeling:** Implementation and comparison of multiple algorithms (e.g., Linear Regression, Decision Trees, Random Forest, XGBoost) to achieve optimal predictive performance.
- **Modular Architecture:** Structured codebase utilizing a custom `src/` package for easy maintainability and scalability.

## 🗂️ Repository Structure

The project directory is structured for clean code practices, reproducibility, and deployment:

```text
GEMSTONE-Price-Prediction/
├── artifacts/          # Saved model weights and preprocessor objects (.pkl)
├── data/               # Raw and processed datasets (ignored in version control)
├── notebook/           # Jupyter notebooks containing EDA and model experiments
├── src/                # Core Python package (data ingestion, transformation, model training)
├── .gitignore          # Standard Python gitignore
├── README.md           # Project documentation
├── requirements.txt    # Project dependencies
└── setup.py            # Package installation setup


🛠️ Tech Stack
Language: Python

Data Manipulation & Analysis: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn, XGBoost

Environment & Package Management: setuptools

🚀 Getting Started
Prerequisites
Ensure you have Python 3.8+ installed. It is highly recommended to use an isolated virtual environment.

Installation
Clone the repository:

Bash
   git clone [https://github.com/Prabhav54/GEMSTONE-Price-Prediction.git](https://github.com/Prabhav54/GEMSTONE-Price-Prediction.git)
   cd GEMSTONE-Price-Prediction
Set up a virtual environment:

Bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:

Bash
   pip install -r requirements.txt
   pip install -e .  # Installs the local src/ package via setup.py
Usage
To train the model and generate the prediction artifacts, run the main training pipeline from the source directory:

Bash
python src/pipelines/training_pipeline.py
(Note: Adjust the script path based on your exact src folder structure).

🧑‍💻 About the Developer
Prabhav Khare 3rd-year Chemical Engineering Student @ National Institute of Technology (NIT) Rourkela

Passionate about bridging core engineering with advanced computational techniques. Actively building automated pipelines, developing data science solutions, and exploring the intersection of machine learning, impactful UI/UX design, and complex problem-solving.
