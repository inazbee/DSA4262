**Assignment 2 – Stress Detection in Reddit Posts**

This project builds a binary classification model to detect stress signals in Reddit posts using the Dreaddit dataset.

**Objective**

To distinguish between “Stressed” and “Non-stressed” posts across multiple Reddit communities and analyse model behaviour beyond predictive performance.

**Model Approach**

- Text features (TF-IDF)

- Pre-computed LIWC & sentiment features

- Logistic Regression and Random Forest comparison

- Hyperparameter tuning with cross-validation

- SHAP-based interpretability analysis

**Final Test Performance**

F1-score: ~0.766

**Additional Analyses**

- Subreddit-level performance comparison

- Error analysis of high-confidence misclassifications

- Feature-level interpretation of stress indicators

- Ethical considerations for deployment

**How to Run**

1. Install required packages (scikit-learn, pandas, shap, matplotlib, etc.)

2. Open dsa4262 assignment 2.ipynb

3. Run all cells sequentially