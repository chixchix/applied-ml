# applied-ml
# Applied Machine Learning Implementations

A collection of machine learning models and data pipelines implemented from scratch. These projects focus on exploring the underlying mathematics and internal logic of core algorithms, independent of high-level ML libraries.

# Key Projects & Metrics
Model Implementations: Hand-coded models handling diverse datasets, including rental data, drone cost estimations, and MNIST.

Data Pipelines: End-to-end data cleaning, preprocessing, and feature engineering.

Evaluation: Rigorous performance analysis focusing on navigating precision-recall trade-offs, maximizing F1-scores, and minimizing RMSE.

Data Engineering Pipeline: A comprehensive data preparation notebook focused strictly on cleaning, imputing missing values, and engineering categorical/numerical features to construct a model-ready dataset.

Demographic & Behavioral Classification: A complex societal dataset by architecting automated preprocessing pipelines using ColumnTransformer for mixed data types (imputation, scaling, and encoding). Trained ensemble models (RandomForestClassifier) to predict categorical targets, validating model robustness via k-fold cross-validation and Macro F1-scores.

Predictive Cost Modeling & Classification: Developed dual predictive models for hardware costs. Explored continuous cost estimation (Regression), then binarized the target variable to architect a classifier (SVC with RBF kernel), evaluated final precision and recall via a confusion matrix.


