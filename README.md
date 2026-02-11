
# Insurance Claim Anticipation — concise summary

Predict whether a policyholder will file an insurance claim using tabular data (demographics, health indicators and activity).

**Dataset (columns)**: `age`, `sex`, `bmi`, `steps`, `children`, `smoker`, `region`, `charges`, `insuranceclaim` (target: 1=claimed, 0=not claimed).

**Pipeline (high level)**
- **EDA:** distribution checks, pairplots and correlation analysis.
- **Preprocessing:** drop duplicates, outlier removal (IQR), categorical encoding (one-hot / dummy), standardization of numeric features.
- **Class imbalance handling:** SMOTE to balance classes after cleanup.
- **Feature selection:** VIF, RFE and PCA experiments to assess multicollinearity and dimensionality.
- **Modeling:** trained and compared several classifiers (Logistic Regression, Decision Tree, Random Forest, Naïve Bayes, SVM, KNN, Gradient Boosting, XGBoost) with randomized search hyperparameter tuning where applicable.

**Key results & notes**
- Small dataset (~1.3k rows) and slightly imbalanced — SMOTE used to balance classes.
- Ensemble and boosting methods performed best (Extreme Gradient Boosting showed the top performance). For this task, F1-score was prioritized over raw accuracy.
- Simpler models (e.g., Logistic Regression) are still recommended when interpretability and generalizability matter.


