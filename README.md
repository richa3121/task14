# AI-ML-Task14

Project Overview

The goal of this task is to perform a comparative analysis of multiple machine learning algorithms on a standard dataset. By evaluating metrics such as accuracy, precision, recall, and F1-score, we identify the model that generalizes best for unseen data.

Dataset

Selected Dataset: Breast Cancer Wisconsin (Diagnostic).

Description: Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

Tools Used

Language: Python.

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn.


Model Persistence: Joblib for saving the final model.

Workflow

Preprocessing: Scaled features using StandardScaler to normalize the data.


Splitting: Divided data into 80% training and 20% testing sets using a fixed random state for consistency across models.

Modeling: Trained Logistic Regression, Decision Tree, Random Forest, and SVM.

Evaluation: Calculated performance metrics and compared training vs. testing scores to detect overfitting.

Deliverables Included

Model Comparison Table: comparison_table.csv or printed in the notebook.

Comparison Plot: A bar chart showing metric distribution across models.

Best Saved Model: best_model.pkl.

