# Ethical AI: Fairness and Explainability in Machine Learning

This project is part of Assignment 14 and focuses on building a machine learning model that is ethical, fair, and explainable. Using the UCI Adult Income dataset, we train a logistic regression classifier and assess its performance through both traditional evaluation metrics and fairness/explainability analysis.

 Dataset

- Dataset: UCI Adult Income Dataset
- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- Target variable: Income (<=50K or >50K)
- Sensitive attribute: Sex (Male/Female)

Tools & Libraries Used

- Python (Google Colab)
- scikit-learn
- Fairlearn (for fairness metrics)
- SHAP (for model explainability)
- LIME (for local prediction explanations)
- Pandas, Matplotlib, NumPy

Model Summary

  - Model used: Logistic Regression
  - Preprocessing steps:
  - Dropped missing values
  - Label encoding for categorical features
- Evaluation metrics:
  - Accuracy
  - Confusion matrix
  - Classification report

Fairness Analysis

Using the Fairlearn library, we analyzed the following metrics based on the sensitive attribute (`sex`):
- Selection rate
- False positive rate
- True positive rate

All metrics were grouped by gender and visualized using bar charts.

 Explainability

- SHAP was used to:
  - Generate global feature importance summary plots
  - Create waterfall plots for individual predictions
- LIME was applied for interpretable explanations of single predictions

 Project Files

`ethical_ai_fairness_explainability.ipynb`Complete Google Colab notebook
`Assignment14_Report.pdf 3-page report discussing findings and recommendations
`README.md` Project overview and setup guide 

 How to Run the Notebook

1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Install the required packages:
   python
   !pip install fairlearn shap lime
   Author:
   **OUMAIMA LAMRANI**
