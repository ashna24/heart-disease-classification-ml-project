# Heart Disease Prediction: Custom KNN vs. Logistic Regression

This project aims to predict the presence of heart disease in patients using clinical features. It highlights the difference between building a machine learning algorithm from scratch versus using optimized libraries.

##  Key Features
* **Custom KNN Implementation:** Euclidean distance, neighbor sorting, and majority voting logic built entirely from scratch.
* **Feature Engineering:** * Handling missing values (replacing 0s in Cholesterol/RestingBP with medians).
    * One-Hot Encoding for categorical data.
    * Feature scaling using `StandardScaler`.
* **Model Comparison:** Evaluates a custom-built K-Nearest Neighbors against Scikit-Learn's Logistic Regression.

## Performance Analysis
* **K-Nearest Neighbors (Scratch):** Achieved an optimal accuracy of ~85.5%.
* **Logistic Regression (Library):** Achieved an accuracy of ~83.7%.
* **Metrics:** Includes scratch implementations for Precision, Recall, and F1-Score calculations.

## Tech Stack
* **Python Libraries:** NumPy, Pandas, Scikit-learn, Seaborn, Matplotlib.

## Structure
* `notebooks/ML_MID.ipynb`: Full analysis, data cleaning, and model development.
* `data/heart.csv`: The clinical dataset.
