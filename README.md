# Assignment 3

This repository contains solutions for Assignment 3. Each question is implemented in separate Python files,
and all the scripts run without errors.

---

## File Descriptions

### Question 1 — Statistical Analysis
Loads the crime data from a CSV and computes the following statistic for the `ViolentCrimesPerPop` column:
mean, median, standard deviation, minimum, and maximum. Then we compare mean and median to determine whether the
distribution is symmetric or skewed, and explains which statistic is more affected by extreme values.

---

### Question 2 — Data Visualization
Loads the crime data from a CSV and creates two plots for the `ViolentCrimesPerPop` column using matplotlib.
Creates a histogram showing the distribution of the values and a box plot showing the median and spread.
Both plots include a title, x-axis label, and y-axis label. Describes what each plot reveals about the
data distribution and whether outliers are present.

---

### Question 3 — Train/Test Split
Loads kidney disease data from CSV and prepares it for machine learning.  Creates a feature matrix `X` and label vector `y` using the `classification` column, then splits the data
into 70% training and 30% testing sets using a fixed random state. Explains why training and testing on
the same data is problematic and describes the purpose of the testing set.

---

### Question 4 — KNN Classifier and Evaluation
Uses the training and testing data from Question 3 to train a K-Nearest Neighbors classifier with k=5.
Makes predictions on the test set and computes the confusion matrix, accuracy, precision, recall, and
F1-score. Explains what the true positive, true negative, false positive, and false negative mean in the
context of kidney disease prediction, why accuracy alone is insufficient, and which metric is the most
important when missing a disease case is serious.

---

### Question 5 — Optimal K Selection
Trains multiple KNN models using k = 1, 3, 5, 7, 9 on the same training and testing data. Records the
test accuracy for each k and displays a results table. Identifies the best k value. Explains how changing k affects model behavior, why small k values cause
overfitting, and why large k values cause underfitting.

---