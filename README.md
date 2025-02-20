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
```

## 🚀 Usage Instructions
1️⃣ Load the Data

Start by exploring the raw Iris dataset or the cleaned version using EDA.ipynb.
2️⃣ Perform Data Preprocessing

Handle missing values and inconsistencies (already done in Cleaned_Iris.csv).
3️⃣ Train ML Models

Open and run the respective notebooks to train models on the dataset.
4️⃣ Evaluate Performance

Analyze accuracy scores, confusion matrices, and classification reports to determine the best-performing model.
📊 Project Summary
✅ Dataset: Iris dataset (4 features, 3 species)
✅ Objective: Identify the best ML model for Iris flower classification
✅ Techniques Used: EDA, Data Preprocessing, KNN, SVM, Random Forest, Neural Networks, Boosting Algorithms

📜 License & Acknowledgments
Developed by Sambit Sahoo, Kirti Agrawal, and Nirman Jaiswal under the supervision of Prof. Samiran Das as part of the DSE315 Data Science in Practice course project.