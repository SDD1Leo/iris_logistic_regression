# Iris Species Classification Project

This project demonstrates a complete machine learning workflow for classifying Iris flower species based on their sepal and petal measurements. It includes data loading, exploratory data analysis (EDA), preprocessing, model training, hyperparameter tuning, evaluation, and an interactive prediction interface.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Steps](#key-steps)
- [Technologies Used](#technologies-used)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [Interactive Prediction](#interactive-prediction)

## Project Overview
This notebook showcases the process of building a classification model for the famous Iris dataset. We utilize Logistic Regression, perform hyperparameter tuning using GridSearchCV, and provide a user-friendly interface for real-time predictions.

## Dataset
The project uses the classic Iris dataset, which contains 150 samples of Iris flowers from three different species (setosa, versicolor, virginica), with four features each: sepal length, sepal width, petal length, and petal width.

## Key Steps
1.  **Environment Setup & Data Loading**: Import necessary libraries and load the Iris dataset into a pandas DataFrame.
2.  **Exploratory Data Analysis (EDA)**: Visualize data distributions, correlations, and relationships between features and species using histograms, box plots, correlation heatmaps, violin plots, and pair plots.
3.  **Data Preprocessing**: Split the dataset into training and testing sets and scale numerical features using `StandardScaler`.
4.  **Model Training**: Train a `LogisticRegression` model on the scaled training data.
5.  **Hyperparameter Tuning**: Optimize the `LogisticRegression` model using `GridSearchCV` to find the best hyperparameters (e.g., `C`, `penalty`).
6.  **Model Evaluation**: Assess the model's performance using metrics like accuracy, precision, recall, F1-score, and a confusion matrix on the test set.
7.  **Prediction on New Data**: Demonstrate how to make predictions on new, unseen data points.
8.  **Interactive Prediction Interface**: Provide an `ipywidgets`-based interface for users to input custom feature values and get instant species predictions.

## Technologies Used
-   Python
-   Pandas (for data manipulation)
-   NumPy (for numerical operations)
-   Matplotlib & Seaborn (for data visualization)
-   Scikit-learn (for machine learning models and preprocessing)
-   ipywidgets (for interactive UI)

## How to Run the Notebook
1.  **Open in Google Colab**: This notebook is designed to run seamlessly in Google Colab. Simply upload the `.ipynb` file to your Colab environment or open it directly if it's hosted online.
2.  **Run All Cells**: Execute all cells in the notebook sequentially. This will load the data, perform EDA, train the model, and set up the interactive prediction tool.

## Interactive Prediction
After running all cells, an interactive widget will appear at the end of the notebook. You can:
1.  Enter values for 'sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', and 'petal width (cm)' into the input boxes.
2.  Click the "Predict Species" button.
3.  The widget will then display the user input, the scaled data, and the predicted Iris species.
