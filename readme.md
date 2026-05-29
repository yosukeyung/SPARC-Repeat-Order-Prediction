# 🏍️ SPARC 2026: Repeat Order Prediction 📊

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Type](https://img.shields.io/badge/Type-Group_Project-8A2BE2)
![Achievement](https://img.shields.io/badge/Achievement-National_Finalist-FFD700?style=flat&logo=trophy&logoColor=black)

> **A Cost-Sensitive Machine Learning approach to predict repeat order behavior in the motor vehicle industry and optimize telemarketing operations.**
> _Created for the SPARC National Data Science Competition 2026! 🏆_

## 📖 Project Overview

This repository contains **Team STRIVE's** final submission for the SPARC National Competition 2026 hosted by Universitas Ciputra. The core business objective of this project is to assist automotive companies in determining the priority of follow-up repeat orders based on historical purchasing data.

Instead of just aiming for standard accuracy, our team developed a **Cost-Sensitive Machine Learning Pipeline** utilizing the **LightGBM** algorithm. This approach strategically balances the trade-off between securing potential buyers (_True Positives_) and saving the company's telemarketing budget by aggressively minimizing wrong targets (_False Positives_).

## ✨ Key Features

- **Strategic EDA & Outlier Handling:** Deep dive into the correlations between vehicle pricing (OTR), down payments (DP), and installments to understand customer purchasing power.
- **Robust Preprocessing Pipeline:** Implemented Scikit-Learn pipelines integrating `SimpleImputer`, `StandardScaler`, and `OneHotEncoder` to ensure zero data leakage and high reproducibility.
- **Cost-Sensitive LightGBM:** Deployed a highly efficient LightGBM model that successfully reduced False Positives dramatically (saving operational costs) while maintaining a solid conversion rate for potential buyers.
- **Business-Driven Evaluation:** Model performance was evaluated not just on statistical metrics (ROC-AUC), but on real-world business impact and ROI.

## 🤝 My Role & Contributions

In this group project, I took the lead on the **Exploratory Data Analysis (EDA)** phase, which laid the critical foundation for our machine learning success. My specific contributions include:

- **Data Deep Dive:** Conducted comprehensive univariate and bivariate analysis to uncover hidden patterns within customer demographics and vehicle transaction data.
- **Feature Correlation & Business Logic:** Mapped out crucial correlations, such as proving the strong positive correlation (0.71) between OTR prices and installments, ensuring our features aligned with real-world business logic.
- **Outlier Management:** Successfully identified and handled massive outliers in the dataset, ensuring the distribution was clean and normalized before being fed into the preprocessing pipeline.

## 🛠️ Tech Stack

- **Python** 🐍 (Core programming language)
- **Pandas & NumPy** 🔢 (Data manipulation and numerical operations)
- **Matplotlib & Seaborn** 🎨 (Data visualization and correlation heatmaps)
- **Scikit-Learn** 🤖 (Preprocessing pipelines and baseline models)
- **LightGBM & XGBoost** 🚀 (Advanced gradient boosting algorithms)

## 📂 Project Structure

```text
├── EDA_FINAL.ipynb              # Notebook containing the Exploratory Data Analysis and data cleaning
├── PreProcessing_FINAL.ipynb    # Notebook detailing the Scikit-Learn preprocessing pipeline
├── ML_FINAL.ipynb               # Notebook for model training, evaluation, and cost-sensitive analysis
├── data_bersih.csv              # Raw data
├── requirements.txt             # List of Python dependencies required to run the app
└── README.md                    # Project documentation
```

## 🚀 Getting Started

To explore our analysis and models locally:

1.  Clone the Repo
    ```bash
    git clone https://github.com/yosukeyung/SPARC-Repeat-Order-Prediction
    cd SPARC-Repeat-Order-Prediction
    ```
2.  Setup Environment
    Ensure you have Python installed. Install the necessary libraries using pip:
    `bash
    pip install -r requirements.txt
    `
3.  Usage
    Launch Jupyter Notebook and run the files in sequential order to understand the full pipeline.
    ```text
    1. Start with EDA_FINAL.ipynb
    2. Proceed to PreProcessing_FINAL.ipynb
    3. Conclude with ML_FINAL.ipynb
    ```

## 👨‍💻 Author

Yosuke Yung
_CS Student @ BINUS UNIVERSITY_
