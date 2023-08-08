# Loan-Default-Prediction-using-Machine-Learning
This project employed multiple machine learning models including Logistic Regression, Decision Trees, Bagging, Random Forest, and Ada Boost, to predict loan sizes for small businesses. The dataset utilized is sourced from the U.S. SBA, an organization that supports and encourages small enterprises in the U.S. credit market

The problem arises from instances of small businesses or startups defaulting on SBA-guaranteed loans. Given the significant role small businesses play in job creation and economic growth, this project aims to create a predictive model to determine the likelihood of a loan being substantial or not. This predictive capability can guide lenders and policymakers in making well-informed choices, thus reducing the risk of loan defaults.

The proposed solution involves applying data mining techniques to construct machine learning models capable of forecasting whether a loan for a small business will be larger than $50,000. Several models, including logistic regression, decision trees, bagging, random forests, and ada boost, will be trained and evaluated. The best-performing model will be selected to ensure accurate and reliable predictions of loan outcomes.

Hyperparameter tuning through cross-validation and grid search will be employed to enhance the model's performance and generalizability to new data. Ultimately, the project aims to support the growth and success of small businesses, contributing to positive economic and social impacts.

The dataset contains 27 variables encompassing details about loans given by the SBA to small businesses. Information about borrowers, banks, loan amounts, loan status, and other pertinent factors is included in these variables.

The project utilized various machine learning models, including Logistic Regression, Decision Trees, Bagging, Random Forest, and Ada Boost, to predict loan sizes for small businesses. The results revealed that all models, except Logistic Regression, achieved a perfect Matthews Correlation Coefficient (MCC) of 1.000 and zero test error, accurately predicting loan defaults. However, the logistic regression model performed well with an MCC of 0.934 and a test error of 0.032. The ensemble models (Decision Trees, Bagging, Random Forest, and Ada Boost) achieved 100% accuracy, suggesting potential overfitting due to the small sample size.

While the ensemble models' accuracy is impressive, it may be a sign of overfitting. The logistic regression model, with an accuracy of 0.9818, offers a more realistic performance without overfitting concerns. Its simplicity and interpretability make it a suitable choice for practical applications and stakeholder communication.

In conclusion, selecting logistic regression over models with perfect accuracy is prudent. The project demonstrated that machine learning can effectively predict loan outcomes for small businesses, aiding lending decisions. It emphasizes the importance of considering both accuracy and model interpretability when addressing real-world business challenges.
