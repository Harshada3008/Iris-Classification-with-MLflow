# Iris-Classification-with-MLflow
<img width="1897" height="746" alt="Screenshot 2025-08-26 175433" src="https://github.com/user-attachments/assets/54a67dcb-3872-4276-a85e-58440a2110da" />
<img width="1919" height="1048" alt="Screenshot 2025-08-26 175505" src="https://github.com/user-attachments/assets/6cd67e59-5d1d-4f52-b48b-b603a620f70c" />
<img width="1879" height="811" alt="Screenshot 2025-08-26 175611" src="https://github.com/user-attachments/assets/00dbf12f-ab17-481d-9ae1-4fe2a1c8f239" />
<img width="1715" height="852" alt="Screenshot 2025-08-26 175709" src="https://github.com/user-attachments/assets/797549b3-3073-4749-a56c-d1660a499216" />
<img width="1834" height="906" alt="Screenshot 2025-08-26 175736" src="https://github.com/user-attachments/assets/35d02d79-fc5f-4578-9d14-40fbbf78062f" />








Iris Classification with MLflow 🌸 – A Random Forest model for classifying Iris flowers, fully tracked using MLflow. Logs parameters, metrics, datasets, and models for reproducibility. Includes evaluation with accuracy, classification report, feature importance, and MLflow UI links for experiment tracking.
🌸 Iris Classification with MLflow
📌 Overview

This project demonstrates building, training, and tracking a Random Forest Classifier on the Iris dataset using MLflow. It highlights how to manage machine learning experiments, log parameters, metrics, models, and datasets for reproducibility and monitoring. The goal is to show best practices in experiment tracking and model management.

🔹 How It Works

Dataset Loading – Uses the Iris dataset from sklearn.datasets.

Data Splitting – Divides data into training (80%) and testing (20%) sets.

MLflow Experiment Setup – Sets the experiment name and tracking URI for logging.

Model Training – Trains a Random Forest Classifier with hyperparameters like n_estimators, max_depth, and random_state.

Logging with MLflow – Logs parameters, metrics (accuracy, train/test size), dataset info, and the trained model.

Evaluation – Calculates accuracy, prints the classification report, and analyzes feature importance.

Experiment Monitoring – Provides run ID, experiment ID, and links to view runs in the MLflow UI.

✨ Key Features

🌿 Random Forest Classifier – High-performance ML model for multi-class classification.

📈 Experiment Tracking – Logs parameters, metrics, and models using MLflow.

📝 Model Reproducibility – Easy to reproduce experiments with logged parameters and datasets.

🔍 Evaluation & Insights – Provides classification report and feature importance analysis.

💻 MLflow Integration – Includes run links, experiment IDs, and UI access for tracking experiments.

🛠️ Tech Stack

Programming Language: Python

Libraries: scikit-learn, pandas, MLflow

Tools: MLflow Tracking Server / MLflow UI

🚀 Benefits

Enables reproducible machine learning experiments

Simplifies logging of parameters, metrics, and models

Helps monitor model performance and feature importance

Facilitates collaboration and experiment tracking across teams

🎯 Conclusion

This repository demonstrates end-to-end machine learning workflow with MLflow, from data preparation to model training, evaluation, and experiment tracking. It is ideal for learning how to manage ML experiments efficiently and integrate MLflow into real-world projects for tracking models and metrics.
