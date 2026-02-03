# Heart Disease Classification using KNN

This project implements a K-Nearest Neighbors (KNN) classifier to predict heart disease with **96.1% accuracy**.

## Key Features
* **Preprocessing:** Utilized `StandardScaler` to normalize feature scales, which improved accuracy from ~86% to 96%.
* **Hyperparameters:** Optimized using `Manhattan` distance and `n_neighbors=3`.
* **Validation:** Robustly tested using 5-Fold Stratified Cross-Validation (Std Dev: 0.0145).

## Technologies Used
* Python, Pandas, Scikit-Learn