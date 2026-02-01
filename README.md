# Machine Learning with Python

A collection of **machine learning projects and exercises** in Python, implemented using **Google Colab** notebooks.  
This repository is intended for **learning, practicing, and experimenting** with core ML concepts and algorithms using real & synthetic datasets.

---

## Notebooks Included

## 1. Supervised Learning

### Linear Models (Foundational)
- **`Supervised Learning/Linear_Models/Linear_Regression_Basics.ipynb`** — Fundamentals of linear regression and evaluation techniques.  
- **`Supervised Learning/Linear_Models/Ridge_and_Lasso_Regression_Basics.ipynb`** — Introduction to Ridge & Lasso regularized regression and the effect of `alpha`.  
- **`Supervised Learning/Linear_Models/Logistic_Regression_and_LinearSVC_Basics.ipynb`** — Basics of logistic regression and LinearSVC classifiers.  
- **`Supervised Learning/Linear_Models/logistic_regression_regularization_breast_cancer.ipynb`** — Logistic regression with regularization on the Breast Cancer dataset.  
- **`Supervised Learning/Linear_Models/LinearSVC_Multiclass_One_vs_Rest.ipynb`** — Multiclass classification using LinearSVC with one-vs-rest strategy.

### Instance-based & Bayes
- **`Supervised Learning/Naive_Bayes_Classifiers/naive_bayes_basics.ipynb`** — GaussianNB, BernoulliNB, and MultinomialNB examples with guidance on usage.  
- **`Supervised Learning/KNN/KNN_Classification_and_Regression.ipynb`** — KNN exercises covering classification and regression.  
- **`Supervised Learning/KNN/Iris_Species_Classification.ipynb`** — Classifying Iris species using the KNN classifier.

### Decision Trees & Ensembles
- **`Supervised Learning/Decision_Trees/Decision_tree_basics.ipynb`** — Decision tree fundamentals, splitting criteria, and visualization.  
- **`Supervised Learning/Ensemble_methods/Random_Forest_Classification.ipynb`** — Random Forest classification and feature importance analysis.  
- **`Supervised Learning/Ensemble_methods/Gradient_Boosting_Classification.ipynb`** — Gradient Boosting classifiers with parameter effects and examples.

### Support Vector Machines (SVM)
- **`Supervised Learning/SVM/svm_with_and_without_scaling.ipynb`** — Demonstrates the effect of scaling on SVM performance.  
- **`Supervised Learning/SVM/svm_scaling_minmax_vs_standard.ipynb`** — Comparison between MinMaxScaler and StandardScaler for SVM.

### Neural Networks
- **`Supervised Learning/Neural_Networks/MLPClassifier_Breast_Cancer_Scaling.ipynb`** — MLPClassifier on Breast Cancer dataset; examines scaling and training behavior.

---

## 2. Unsupervised Learning
- **`Unsupervised Learning/Agglomerative_Clustering/Agglomerative_Clustering.ipynb`** — Hierarchical agglomerative clustering with dendrogram visualization.  
- **`Unsupervised Learning/DBSCAN_Clustering/DBSCAN_clustering.ipynb`** — DBSCAN clustering, handling noise, and parameter selection.  
- **`Unsupervised Learning/K-Means Clustering/KMeans_Clustering.ipynb`** — K-Means clustering with visualizations and comparison with PCA/NMF.

---

## 3. Preprocessing
- **`Preprocessing/data_preprocessing_minmaxscaler.ipynb`** — Data scaling using MinMaxScaler and why scaling matters for ML models.

---

## 4. Model Evaluation & Validation
- **`Model Evaluation/Cross_Validation_Strategies.ipynb`** — k-fold and stratified cross-validation, evaluation metrics, and best practices.

---

## 5. Pipelines & Model Composition
- **`Pipelines/Algorithm_Chains_and_Pipelines.ipynb`** — Building sklearn pipelines to combine preprocessing and estimators into clean workflows.

---

## 6. Natural Language Processing (NLP)
- **`NLP/IMDB_Sentiment_Analysis.ipynb`** — IMDB sentiment analysis using Bag-of-Words, TF-IDF, and Logistic Regression. Covers data loading, preprocessing, feature extraction, model training, and evaluation using classical NLP techniques.


---

## How to Use
1. Open the notebooks (`.ipynb`) in **Google Colab**  
2. Run the cells sequentially  
3. Observe results and modify code to experiment with parameters  

---

## Requirements
- Python 3.x (already available in Colab)  
- Libraries (pre-installed in Colab, otherwise install via pip):
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
