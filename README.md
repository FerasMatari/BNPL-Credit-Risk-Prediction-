
# 💳 BNPL Credit Risk Prediction

### Machine Learning | Data Science | FinTech

## 📌 Project Overview

This project explores credit risk prediction in Buy Now, Pay Later (BNPL) services using Machine Learning.

The objective is to analyze customer data, identify patterns associated with payment default, and build classification models to support data-driven credit risk assessment.

## 🎯 Business Problem

Buy Now, Pay Later services allow customers to purchase products and pay in installments.

However, customer defaults can create financial risks for BNPL providers.

Machine Learning can help identify customers with a higher likelihood of default and support more informed risk management decisions.

## 📊 Dataset

**Dataset:** Buy Now Pay Later (BNPL) Dataset

**Source:** Kaggle

🔗 [View Dataset on Kaggle](https://www.kaggle.com/datasets/bhanageviraj/buy-now-pay-later-bnpl-dataset)

The dataset is used to explore customer payment behavior and develop credit risk classification models.

## 🔍 Project Workflow

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Feature preparation
5. Training classification models
6. Model evaluation and comparison
7. Interpretation of results

## 🤖 Machine Learning Models

The project explores the following classification algorithms:

- Logistic Regression
- Random Forest
- Gradient Boosting

## 🛠️ Technologies & Tools

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📈 Model Evaluation

Model performance is evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

These metrics help assess the models' ability to identify customers at risk of default.


## 📊 Model Performance Comparison

Three machine learning classification models were evaluated for BNPL credit default risk prediction.

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Random Forest | 0.6240 | 0.5114 | 0.8354 | 0.6344 | 0.7762 |
| Gradient Boosting | 0.6332 | 0.5196 | 0.8057 | 0.6317 | 0.7778 |
| Logistic Regression | 0.6675 | 0.5595 | 0.6980 | 0.6211 | 0.7587 |

### 🔍 Key Findings

- **Random Forest** achieved the highest recall for class 1 (83.54%), making it the preferred model when identifying potential defaulters is the primary objective.
- **Logistic Regression** achieved the highest accuracy (66.75%) and precision (55.95%).
- **Gradient Boosting** achieved the highest ROC-AUC (77.78%).
- The results highlight the trade-off between detecting potential defaulters and minimizing false positive predictions.

### 💡 Business Insight

In BNPL credit risk assessment, failing to identify a customer who may default can result in financial losses.

Therefore, recall for the default class was prioritized as the primary model selection metric.

Random Forest demonstrated the strongest performance on this metric, identifying approximately 83.5% of actual defaulters in the evaluated data.

However, its lower precision indicates that some customers predicted as high-risk may not actually default.


## 💡 Project Applications

- Credit risk assessment
- Customer default prediction
- Financial data analysis
- Risk-based decision support
- Machine Learning in FinTech

## 📂 Repository Structure

- `README.md` — Project documentation
- `BNPL_Credit_Risk_Project.ipynb` — Data analysis and machine learning notebook

## 🚀 Future Improvements

- Explore additional classification algorithms.
- Improve feature engineering.
- Investigate class imbalance handling.
- Apply model explainability techniques such as SHAP.
- Develop an interactive credit risk prediction dashboard.

## 👨‍💻 Author

**Feras Matari**

Data Science Graduate | Jeddah, Saudi Arabia

GitHub: [FerasMatari](https://github.com/FerasMatari)

## 📚 Dataset Credits

Dataset provided by bhanageviraj on Kaggle.

[Original Dataset](https://www.kaggle.com/datasets/bhanageviraj/buy-now-pay-later-bnpl-dataset)
