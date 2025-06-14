# SpaceX Falcon 9 First Stage Landing Prediction

## Project Overview

SpaceX has revolutionized spaceflight by reusing the first stage of its Falcon 9 rockets, significantly lowering launch costs. This project aims to predict whether the first stage will successfully land based on pre-launch features, helping optimize cost predictions and competitive bids.

Using machine learning models, we analyze launch data to classify if the first stage will land or not.

---

## Dataset Description

- **dataset_part_2.csv**: Contains the target variable and additional features.
- **dataset_part_3.csv**: Contains engineered input features used for model training.

---

## Tasks Summary

1. Load and preprocess the data.
2. Standardize features and split into training/testing sets.
3. Train and tune four classifiers using GridSearchCV with 10-fold cross-validation:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Decision Tree
   - K-Nearest Neighbors (KNN)
4. Evaluate models on the test set using accuracy and confusion matrices.
5. Identify the best-performing model based on test accuracy.

---

## Results

- The **Logistic Regression** model performed best, achieving **83.33% accuracy** on the test set.
- Confusion matrices visualize model performance and show the distribution of true/false positives and negatives.

---

## How to Use

1. Clone this repository.
2. Install dependencies from `requirements.txt`.
3. Run the Jupyter notebook or Python scripts to reproduce data preprocessing, model training, and evaluation.

---

## Conclusion

Logistic Regression was the best model in predicting the first stage landing of Falcon 9 rockets. This predictive capability can guide cost-efficient launch planning and support competitive bidding by providing reliable landing forecasts.

---
