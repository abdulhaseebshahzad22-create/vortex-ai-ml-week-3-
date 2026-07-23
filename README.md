# vortex-ai-ml-week-3-
# Regression and Clustering using Machine Learning

## Project Overview

This project was completed as part of my AI & Machine Learning Internship Week 3 task.

The project contains two machine learning tasks:

1. Regression using Linear Regression
2. Clustering using K-Means

The regression model predicts house prices, while the clustering model groups customers based on their income and spending habits.

---

## Datasets Used

### 1. Housing Dataset
- File: `housing(1).csv`
- Target Column: `median_house_value`

### 2. Mall Customers Dataset
- File: `Mall_Customers(1).csv`

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Regression Task

In this task, I:

- Loaded the housing dataset.
- Cleaned the data.
- Converted text data into numbers.
- Split the dataset into training and testing data.
- Trained a Linear Regression model.
- Predicted house prices.
- Evaluated the model using:
  - RMSE
  - R² Score

---

## Clustering Task

In this task, I:

- Loaded the Mall Customers dataset.
- Selected Annual Income and Spending Score.
- Scaled the data using StandardScaler.
- Used the Elbow Method to choose the best number of clusters.
- Applied the K-Means algorithm.
- Visualized the customer groups using a scatter plot.

---

## How to Run

1. Download the project files.
2. Open the notebook in Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Place both datasets in the same folder as the notebook.
5. Run all notebook cells from top to bottom.

---

## Project Files

```
Regression_Clustering.ipynb
housing(1).csv
Mall_Customers(1).csv
README.md
```

---

## Results

The Linear Regression model predicts house prices using the housing dataset.

The K-Means model groups customers into different clusters based on their income and spending score.

Both models were successfully trained and evaluated.

---

## Author

**Abdul Haseeb**

AI & Machine Learning Internship – Week 3
