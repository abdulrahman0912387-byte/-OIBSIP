# Iris Flower Classification

## Objective
This project trains a machine learning classification model to identify the species 
of an iris flower (Setosa, Versicolor, or Virginica) based on its physical 
measurements: sepal length, sepal width, petal length, and petal width.

## Tech Stack
- Python
- pandas
- scikit-learn
- matplotlib / seaborn
- Jupyter Notebook (via VS Code)

## Project Workflow
1. **Data Loading** — Used the built-in Iris dataset from `sklearn.datasets`.
2. **Exploratory Data Analysis (EDA)** — Checked shape, data types, missing values, 
   and descriptive statistics.
3. **Visualizations** — Created a pairplot and box plots to explore how well each 
   feature separates the three species.
4. **Feature Selection Discussion** — Identified petal length and petal width as 
   the most discriminative features.
5. **Train/Test Split** — Split the data 80/20 into training and testing sets.
6. **Model Training** — Trained two classifiers:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
7. **Evaluation** — Assessed both models using accuracy score, confusion matrix, 
   and classification report (precision, recall, F1-score).
8. **Conclusion** — Compared both models and identified the best-performing one.

## Results
- **Logistic Regression Accuracy:** (96%)
- **KNN Accuracy:** (100%)

## How to Run
1. Clone this repository
2. Navigate to this folder: `cd DataScience-Task1-IrisClassification`
3. Create and activate a virtual environment:

## Author
Abdul-Rahman — Oasis Infobyte Data Science Internship