Intern Performance Predictor
What it is

A machine learning project that predicts whether an intern is likely to excel or struggle based on task completion time, feedback ratings, and attendance.

How it works

Uses a Random Forest Classifier in Python.

Trains on past intern data (intern_data.csv) with features:

task_time – time to complete tasks

feedback – feedback rating (1–5)

attendance – attendance percentage (0–1)

Predicts outcome: 1 = Excel, 0 = Struggle.

How to use

Open Intern_Performance_Model.ipynb in Jupyter Notebook.

Make sure intern_data.csv is in the same folder.

Run all cells to train the model and evaluate it.

Add your own intern data in the new_data dataframe to get predictions.

Tools

Python, Pandas, scikit-learn, Matplotlib, Seaborn
