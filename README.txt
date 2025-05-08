This notebook is a notebook for the Data Analytics Competition held by Universitas Gadjah Mada, 2025.

This competition challenges us to develop a machine learning model that can predict whether a mobile app is likely to be at risk of violating COPPA. By identifying potentially non-compliant apps, we can help app stores, developers, and parents create a safer online environment for children. Your model will analyze a variety of app characteristics, including genre, target audience (implied by download ranges), privacy policy features, and developer information, to assess the likelihood of COPPA non-compliance.

The core objective is a binary classification task:
Target Variable: coppaRisk (boolean: true or false) - Predict whether an app is at risk of violating COPPA. true indicates a higher risk of non-compliance, while false suggests a lower risk.

The challenges in this dataset are as follows.

1. Missing Data: The presence of "ADDRESS NOT LISTED IN PLAYSTORE" and "CANNOT IDENTIFY COUNTRY" requires careful handling.
2. Categorical Feature Encoding: You'll need to decide how to encode categorical features.
3. Feature Engineering: You may be able to create new features that are more predictive than the raw data.
4. Imbalanced Data: If the coppaRisk variable shows a significant imbalance (e.g., many more false than true cases).
5. Interpretable Models: Consider using models that are more easily interpretable (e.g., logistic regression, decision trees) to understand why an app is flagged as high-risk. This can be valuable for informing policy and developer guidance.
