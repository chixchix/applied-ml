# Coffee Customer Retention Analysis
This project implements a complete machine learning pipeline to predict customer retention.

### Key Engineering Achievements:
* **Semi-Supervised Learning:** Utilized `LabelSpreading` to infer missing target labels from partially labeled behavioral data.
* **Automated Pipelines:** Built modular `sklearn.Pipeline` objects to ensure consistent preprocessing, dimensionality reduction (PCA/ICA), and model training.
* **Data-Driven Evaluation:** Used `classification_report` to perform a granular analysis of model performance, highlighting strengths in identifying non-returning customers.
