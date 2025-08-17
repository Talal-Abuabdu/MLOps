# MLOps
The notebook demonstrates an MLOps workflow for credit risk classification: loading and preprocessing data, training Logistic Regression, tuning with Hyperopt, and tracking experiments with MLflow, ending with performance evaluation using key classification metrics.

This notebook is a Machine Learning Operations (MLOps) workflow demonstration. It walks through the end-to-end process of:

Setup & Installation

Installs dependencies like mlflow, scikit-learn, pandas, matplotlib, and hyperopt.

Prepares Google Drive integration for storing logs and artifacts.

Data Loading & Preprocessing

Loads a dataset (dataset_.csv).

Renames columns for readability.

Splits the dataset into training and testing sets.

Model Training & Experiment Tracking

Uses MLflow for logging experiments and results.

Implements Logistic Regression as the baseline model.

Hyperparameter Optimization

Uses Hyperopt to search for the best Logistic Regression parameters.

Logs runs and parameters in MLflow for tracking.

Evaluation

Computes classification metrics like accuracy, precision, recall, F1-score, and classification report.

Compares performance across multiple runs.
