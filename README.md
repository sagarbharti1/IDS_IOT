# IDS_IOT

ToN_IoT Intrusion Detection with LSTM and PFI

📌 Project Overview

This project focuses on detecting network intrusions using the ToN_IoT dataset. The approach involves preprocessing the dataset, performing feature selection using Permutation Feature Importance (PFI), handling class imbalance with SMOTE, and training an LSTM model for classification.

🚀 Features Implemented

Data Preprocessing: Normalization using MinMaxScaler.

Feature Selection: Uses PFI (Permutation Feature Importance) to select the top 15 most important features.

Class Imbalance Handling: Oversampling using SMOTE.

Deep Learning Model: LSTM-based neural network for binary classification.

Performance Evaluation: Accuracy, Precision, Recall, F1-score, and Confusion Matrix visualization.

📂 Dataset

Dataset Used: ToN_IoT_preprocessed.csv

🛠 Tech Stack

Programming Language: Python

Machine Learning: Scikit-Learn, Imbalanced-Learn (SMOTE)

Deep Learning: TensorFlow/Keras

Data Visualization: Matplotlib, Seaborn

Results and Analysis

📊 The model's performance is evaluated using:
✅ Accuracy✅ Precision✅ Recall✅ F1-Score✅ Confusion Matrix (Visualized using Seaborn)

🔥 Future Improvements

Experiment with different feature selection methods (e.g., SHAP, Recursive Feature Elimination).

Optimize hyperparameters using Grid Search.

Try other deep learning models like CNN or Transformer-based architecture
