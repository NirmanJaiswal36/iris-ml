# 🌸 Iris Flower Classification using Machine Learning 🌿  

This project is aimed at classifying different species of **Iris flowers** using machine learning models and determining the best-performing algorithm. The dataset used is the **Iris dataset**, which contains measurements of **150** Iris flowers, classified into three species:  
✅ **Iris-setosa**  
✅ **Iris-versicolor**  
✅ **Iris-virginica**  

We apply various **machine learning algorithms** to classify the flowers based on their **sepal and petal measurements**.  

## 📂 Project Structure  

The repository contains the following files:  

📌 **Iris Dataset** (`Iris.csv`)  
- The raw dataset with four features (**sepal length, sepal width, petal length, petal width**) and the corresponding **species label** for each flower.  

📌 **Exploratory Data Analysis (EDA)** (`EDA.ipynb`)  
- A **Jupyter Notebook** for performing **EDA**, including **data cleaning, visualizations, and statistical summaries** to understand the dataset better.  

📌 **Cleaned Iris Dataset** (`Cleaned_Iris.csv`)  
- A **preprocessed version** of the dataset, with missing values handled and necessary data transformations applied.  

📌 **Machine Learning Models Notebooks**  
These notebooks contain **training and evaluation** of different ML models:  
🔹 `K_iris.ipynb` → **KNN, Random Forest, AdaBoost**  
🔹 `S_iris.ipynb` → **Decision Tree, SVM (PCA & Non-PCA), Gaussian Naive Bayes, Gradient Boosting, XGBoost**  
🔹 `N_iris.ipynb` → **Logistic Regression, ANN, Ensemble of Ensembles, CatBoost**  

📌 **Final Project Report** (`CognitiQ_Project_Report.pdf`)  
- A detailed **summary** of the project, including problem statement, dataset description, methodology, evaluation, and conclusions.  

## 🔧 Requirements  

To run the Jupyter Notebooks and models, install the following dependencies:  

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
