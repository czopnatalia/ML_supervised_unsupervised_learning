# Machine Learning Portfolio – Supervised & Unsupervised Learning

## Project Overview
This repository contains a collection of Machine Learning projects focusing on practical applications of predictive modeling, data engineering, and automated pipelines.

## Key Projects

### 1. House Price Prediction (Regression Analysis)
* **Goal:** Predict median house values (MEDV) using neighborhood characteristics.
* **Methodology:** Comparative analysis between Linear Regression and **XGBoost**.
* **Technical Highlight:** Conducted a formal analysis of linear regression assumptions, identifying violations of homoscedasticity and normality, which justified the use of non-linear ensemble methods.
* **Optimization:** Hyperparameter tuning using **GridSearchCV** for the XGBoost model.

### 2. Automated Wine Classification Pipeline
* **Goal:** Classify wine samples into three cultivars based on 13 physicochemical attributes.
* **Pipeline Design:** Utilized `sklearn.pipeline.Pipeline` to prevent data leakage and automate the workflow from standardization to prediction.
* **Models:** Comparison of **Random Forest** (found to be more stable) and **k-Nearest Neighbors**.
* **Insights:** Demonstrated the critical role of data scaling (StandardScaler) in distance-based algorithms like k-NN.

### 3. Subsurface Data Clustering ("Volve" Dataset)
* **Goal:** Uncover hidden patterns in geological and geophysical data from the North Sea.
* **Application:** Segmentation of stratigraphic layers through unsupervised clustering techniques.

### 4. Advanced Feature Engineering Lab
* **Focus:** Handling high cardinality, missing data imputation, and data splitting strategies.
* **Key Techniques:** Implementation of **KNN Imputer** and **Iterative Imputer** vs. simple fill-methods to preserve data distribution.
* **Stratification:** Utilized stratified splitting to ensure consistent class proportions across training and test sets.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn, TensorFlow/Keras.
* **Tools:** Jupyter Notebooks, Google Colab.

## Key Achievements
* Achieved **99.4% accuracy** in classification tasks through Random Forest optimization.
* Developed end-to-end pipelines that ensure code reproducibility and scalability.
