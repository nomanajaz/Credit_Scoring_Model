
## Introduction

We are excited to introduce our latest development - a Credit Scoring Model designed to predict the creditworthiness of individuals based on historical financial data. This model utilizes machine learning algorithms to provide accurate assessments, assisting financial institutions in making informed decisions regarding credit risk.

## Key Highlights

### High Accuracy

- Our **Random Forest Model** achieved an impressive **82% accuracy** with an **ROC AUC score of 0.724**. It excels in identifying risky credit cases with a **96% recall** for the risky category.

### Robust Performance

- The **XGBoost Model** delivered strong results with **79% accuracy** and an **ROC AUC score of 0.718**.
- The **Best Tuned Model** (XGBoost) achieved **78.5% accuracy** and an **ROC AUC score of 0.705**.

## Detailed Metrics

### Random Forest Model
- Non-risky cases: Precision **0.83**, Recall **0.49**.
- Risky cases: Precision **0.82**, Recall **0.96**.

### XGBoost Model
- Non-risky cases: Precision **0.68**, Recall **0.54**.
- Risky cases: Precision **0.82**, Recall **0.89**.

### Best Tuned Model
- Non-risky cases: Precision **0.68**, Recall **0.51**.
- Risky cases: Precision **0.81**, Recall **0.90**.

## Confusion Matrix Insights

- Out of 59 actual non-risky cases, 30 were correctly predicted as non-risky.
- Out of 141 actual risky cases, 127 were correctly predicted as risky.

## Technologies Used

- **Random Forest Classifier** and **XGBoost Classifier**.
- Libraries: **Scikit-learn** and **XGBoost**.
- Tools: **Pipeline** and **GridSearchCV** for optimal model performance.

## Conclusion

Our Credit Scoring Model is poised to revolutionize credit risk assessment in the financial sector. The Random Forest model, in particular, stands out for its high accuracy and effectiveness in detecting risky cases. We are proud of this achievement and eager to see its impact unfold.

Stay tuned for more updates!

## Keywords

CreditScoring, MachineLearning, FinancialData, DataScience, CreditRisk, AI, ModelDevelopment
