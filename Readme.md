Intern Performance Predictor
Project Overview

This project predicts intern performance (excel or struggle) based on task completion time, feedback ratings, and attendance.
It uses a Random Forest Classifier to determine which interns are likely to excel or struggle.

Dataset

intern_data.csv contains:

Column	Description
intern_id	Unique ID for each intern
task_time	Average time to complete tasks (minutes)
feedback	Feedback rating (1–5)
attendance	Attendance fraction (0.0–1.0)
outcome	Label: 1 = Excel, 0 = Struggle
Approach

Load and inspect the dataset using Pandas.

Split data into features (task_time, feedback, attendance) and target (outcome).

Train a Random Forest Classifier on the training set.

Evaluate the model using accuracy, classification report, and confusion matrix.

Visualize feature importance to see which factors influence performance.

Predict performance for new interns.

How to Run

Clone or download this repository.

Make sure intern_data.csv is in the same folder as the notebook.

Open Intern_Performance_Model.ipynb in Jupyter Notebook.

Run all cells to train the model and make predictions.

Optional: Modify the new_data dataframe to predict performance for other interns.

Results

Model predicts which interns are likely to excel or struggle.

Accuracy on test data: ~0.8 (may vary depending on dataset).

Feature importance and confusion matrix visualizations help understand model behavior.

Tools & Libraries

Python

Pandas

scikit-learn

Matplotlib & Seaborn
