# Credit Risk Assessment Model

Background:

Financial institutions face challenges in accurately assessing borrower creditworthiness. Inaccurate loan approval decisions can lead to revenue loss from defaults or missed opportunities with creditworthy applicants. This project aims to improve loan approval systems by predicting whether an application should be approved based on borrower data. 
In addition, the model highlights features that play the most significant role in a borrower’s likelihood of default, providing actionable insights for risk management.

Dataset:
Publicly available credit risk dataset containing loan details, repayment history, and financial indicators.

Approach:
* Preprocessed and cleaned missing/imbalanced data.
* Engineered key features (debt-to-income ratio, credit history length, etc.).
* Trained classification models (Logistic Regression, XGBoost, SVM).
* Evaluated models using AUC, precision, recall, and F1-score.
* Used feature importance (via XGBoost and SHAP values) to identify top risk factors.

Results:
* Logistic Regression achieved an F1-score of 79%, balancing approval and default prediction.
* Identified income level, loan amount, credit history length, and debt-to-income ratio as top predictors of default.
* Produced clear visualizations of feature contributions for business interpretability.

Impact:
* Helps lending teams make data-driven approval decisions.
* Provides transparency by highlighting why applicants are considered risky.
* Supports revenue growth by reducing default risk while approving more low-risk applicants.

Tech Stack:
Python, Scikit-learn, XGBoost, Logistic Regression, SVM, Pandas, Matplotlib/Seaborn, SHAP
