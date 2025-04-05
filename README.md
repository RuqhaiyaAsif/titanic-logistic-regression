# Titanic-logistic-regression
This project predicts survival on the Titanic using machine learning, specifically **Logistic Regression**. The dataset is the classic Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic).

# Project Goals

- Perform data cleaning and preprocessing.
- Apply logistic regression for binary classification.
- Evaluate model using confusion matrix and classification metrics.
- Visualize results for better understanding.

  # ML Model

- **Logistic Regression** using `sklearn`
- Train/test split: 80/20
- Evaluation:
  - Accuracy
  - Precision, Recall, F1 Score
  - Confusion Matrix
 
  # Results

- Achieved around ~78% accuracy
- Model performs well on classifying survivors vs. non-survivors
- Future improvements: try Decision Trees, Random Forests, and hyperparameter tuning

<img width="452" alt="tlr" src="https://github.com/user-attachments/assets/68ae674c-dcd1-4390-b185-eff1aee7e733" />

# Insights from Model Evaluation
Decision Tree achieved slightly higher accuracy and F1-score than Logistic Regression, indicating better overall performance in classifying both survivors and non-survivors.

Logistic Regression, however, showed higher precision, meaning it was more conservative and made fewer false positive errors (i.e., fewer cases of wrongly predicting a person would survive).

This trade-off is important in real-world applications:

✅ Use Decision Tree when balanced classification matters (you want to detect both survivors and non-survivors well).

✅ Use Logistic Regression when false positives are riskier, e.g., allocating life-saving resources.
