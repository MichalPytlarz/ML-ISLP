# ISLP Solutions - Statistical Learning with Python 🐍

This repository contains my solutions to the labs and exercises from the book **"An Introduction to Statistical Learning with applications in Python" (ISLP)**. This project serves as a comprehensive documentation of my journey through the mathematical and practical foundations of Machine Learning.

### ⚙️ Core Concepts 
I implemented and analyzed the following statistical methods:
* **Regression:** Simple & Multiple Linear Regression, Polynomial Regression.
* **Classification:** Logistic Regression, LDA, QDA, Naive Bayes, K-Nearest Neighbors (KNN).
* **Resampling Methods:** K-Fold Cross-Validation, Bootstrapping.
* **Linear Model Selection:** Subset Selection, Ridge & Lasso Regression (Regularization).
* **Tree-Based Methods:** Decision Trees, Random Forests, Bagging, and Boosting.
* **Unsupervised Learning:** Principal Component Analysis (PCA), K-Means, and Hierarchical Clustering.

### 🛠️ Tech Stack
* **Core Libraries:** * `ISLP`
    * `scikit-learn` (model implementation and evaluation)
    * `statsmodels` (detailed statistical inference, p-values, and R-squared analysis)
    * `pandas` & `numpy` (data manipulation)
    * `matplotlib` & `seaborn` (diagnostic plotting and EDA)

### 📂 Repository Structure
The solutions are organized by chapter. Each directory contains a Jupyter Notebook (`.ipynb`) with commented code and statistical interpretations:
* `/ch03_linear_regression` - Diagnostic plots, multicollinearity analysis (VIF).
* `/ch04_classification` - Comparing classifiers on the `Smarket` and `Default` datasets.
* `/ch06_linear_model_selection` - Implementing Lasso to perform feature selection.
* `/Main_Project` - The Main Project for detection heart-disease (with my comments why do i make each decision) -> Project involves parts: Data Analysis, ML, statistics and Data Visualization

### 📈 Key Insights
> [!IMPORTANT]
> A major focus of this project was the **Bias-Variance Tradeoff**. By implementing Lasso and Ridge regression, I demonstrated how regularization can prevent overfitting and improve model interpretability in high-dimensional datasets.

### 🚀 Getting Started
1. Clone this repository: `git clone https://github.com/your-username/islp-solutions.git`
2. Install the required ISLP library:
   ```bash
   pip install ISLP
