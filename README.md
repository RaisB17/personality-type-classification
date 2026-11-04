# MBTI Personality Type Classification

## Project Overview

This project focuses on analyzing and classifying personality types based on the Myers-Briggs Type Indicator (MBTI) using machine learning algorithms.

The project covers data understanding, exploratory data analysis (EDA), data preprocessing, feature selection, model development, evaluation, and deployment planning using Streamlit.

## Dataset

The dataset contains **43,744 records** and **9 features**, including:

- Age
- Gender
- Education
- Introversion Score
- Sensing Score
- Thinking Score
- Judging Score
- Interest
- Personality

Dataset source: [MBTI Dataset](https://github.com/naufalfrdss/Data_Sains/blob/main/datakotor.csv)

## Project Workflow

1. **Business Understanding** – Understanding the project's objectives and classification problem.
2. **Exploratory Data Analysis (EDA)** – Exploring data distributions and relationships between features.
3. **Data Preprocessing** – Handling missing values, duplicate records, categorical encoding, outliers, and class imbalance.
4. **Feature Selection** – Applying SelectKBest and comparing feature importance across machine learning models.
5. **Modeling** – Training and evaluating Random Forest, Gradient Boosting, and XGBoost.
6. **Deployment** – Selecting Streamlit for application deployment.

## Methods and Techniques

- Missing value and duplicate handling
- Label Encoding
- Interquartile Range (IQR) for outlier handling
- RandomOverSampler for class balancing
- SelectKBest for feature selection
- StandardScaler, MinMaxScaler, and RobustScaler
- Random Forest
- Gradient Boosting
- XGBoost
- Streamlit for deployment

## Model Evaluation

The models were evaluated using Accuracy, Precision, Recall, and F1-Score.

The best result was achieved by **Random Forest with IQR preprocessing**.

| Metric | Score |
|---|---:|
| Accuracy | 93.76% |
| Precision | 93.81% |
| Recall | 93.76% |
| F1-Score | 93.76% |

## Repository Structure

```text
personality-type-classification/
├── notebooks/
│   ├── README.md
│   └── personality_type_classification.ipynb
├── .gitignore
└── README.md
```

## Contributors

- Muhammad Rais Asy Syauqi
- Muhammad Naufal Firdaus
- Hasan Al Banna

---

This project was developed as part of a Data Science and Analytics project.
