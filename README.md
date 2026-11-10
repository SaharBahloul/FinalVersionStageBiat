
# 🏦 Banking Customer Segmentation Using Unsupervised Machine Learning

### Data Science & AI Internship | BIAT – Banque Internationale Arabe de Tunisie | 2025

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Unsupervised-008080)

---

## 📌 Project Overview

This project was developed during my **Data Science & Artificial Intelligence internship at BIAT (Banque Internationale Arabe de Tunisie)** in 2025.

The objective was to explore financial data and apply **unsupervised machine learning techniques** to identify meaningful patterns and discover customer segments.

The project covers key stages of a Data Science workflow, from data preprocessing and exploratory analysis to dimensionality reduction, clustering, and model comparison.

### 🎯 Main Objectives

- Explore and understand high-dimensional financial datasets.
- Identify relationships and correlations between variables.
- Build automated data preprocessing pipelines.
- Apply and compare unsupervised machine learning algorithms.
- Use dimensionality reduction techniques to explore customer structures.
- Support data-driven analysis in a banking context.

---

## 📊 Dataset & Data Preparation

The internship involved analyzing a financial dataset containing:

- **300,000+ observations**
- **157 financial variables**
- Numerical and potentially correlated features
- Sensitive banking information requiring confidentiality

### Data Preprocessing

The workflow included:

- Missing-value analysis and handling
- Outlier detection and treatment
- Feature normalization and scaling
- Correlation analysis
- Preparation of datasets for clustering

These steps helped prepare the data for further statistical analysis and machine learning.

**Confidentiality:** The original banking dataset is not included in this public repository.

---

## 🔍 Exploratory Data Analysis

Exploratory analysis was used to understand the structure of the financial data and identify potential relationships between variables.

### Correlation Analysis

Three correlation methods were explored:

| Method | Purpose |
|---|---|
| Pearson | Identify linear relationships |
| Spearman | Analyze monotonic relationships |
| Kendall | Evaluate rank-based associations |

The repository includes correlation analysis outputs and filtered results.

---

## 🧠 Machine Learning Approach

### 1. K-Means Clustering

Partition-based clustering to identify groups of observations based on feature similarity.

### 2. DBSCAN

Density-based clustering to identify dense groups and potentially unusual observations.

### 3. Gaussian Mixture Models (GMM)

Probabilistic clustering approach that represents data as a mixture of Gaussian distributions.

### 4. Principal Component Analysis (PCA)

Linear dimensionality reduction technique used to explore the structure of high-dimensional data.

### 5. UMAP

Nonlinear dimensionality reduction technique used to investigate local and global data structures.

---

## ⚙️ Machine Learning Pipeline

```text
Financial Data
      |
      v
Data Quality Assessment
      |
      v
Missing Values & Outlier Treatment
      |
      v
Feature Scaling & Normalization
      |
      v
Exploratory & Correlation Analysis
      |
      v
Dimensionality Reduction
    PCA / UMAP
      |
      v
Unsupervised Learning
 K-Means / DBSCAN / GMM
      |
      v
Clustering Comparison
      |
      v
Interpretation & Analysis
```

---

## 📁 Repository Structure

The repository contains:

| File | Description |
|---|---|
| [finalversion.ipynb](finalversion.ipynb) | Main Jupyter notebook containing the project analysis and implementation |
| [Correlation_Results.xlsx](Correlation_Results.xlsx) | Correlation analysis results |
| [Correlation_Results_Interpreted.xlsx](Correlation_Results_Interpreted.xlsx) | Interpreted correlation outputs |
| [cluster_comparison_results.xlsx](cluster_comparison_results.xlsx) | Clustering comparison results |
| [correlation_full_pearson.xlsx](correlation_full_pearson.xlsx) | Full Pearson correlation results |
| [correlation_full_spearman.xlsx](correlation_full_spearman.xlsx) | Full Spearman correlation results |
| [correlation_full_kendall.xlsx](correlation_full_kendall.xlsx) | Full Kendall correlation results |
| [correlation_filtered_pearson.xlsx](correlation_filtered_pearson.xlsx) | Filtered Pearson correlations |
| [correlation_filtered_spearman.xlsx](correlation_filtered_spearman.xlsx) | Filtered Spearman correlations |
| [correlation_filtered_kendall.xlsx](correlation_filtered_kendall.xlsx) | Filtered Kendall correlations |
| [Internship Report](Sahar%20Bahloul_INT%20102%20_%20Internship%20Report.pdf) | Internship project report |

---

## 🛠️ Technologies & Tools

**Programming:** Python

**Data Manipulation:** Pandas, NumPy

**Machine Learning:** scikit-learn

**Clustering:** K-Means, DBSCAN, Gaussian Mixture Models

**Dimensionality Reduction:** PCA, UMAP

**Data Analysis:** Statistical Analysis, Correlation Analysis, Feature Scaling

**Development Environment:** Jupyter Notebook

**Methodology:** CRISP-DM

---

## 💡 Skills Demonstrated

This project highlights practical experience in:

- Working with large, high-dimensional financial datasets
- Building machine learning preprocessing pipelines
- Applying unsupervised learning methods
- Comparing different clustering approaches
- Exploring dimensionality reduction techniques
- Interpreting statistical relationships
- Working with confidentiality constraints in the financial sector

---

## 🔐 Data Confidentiality

This project was developed during an internship in the banking sector.

The original dataset and any confidential customer information are not intended for public distribution.

The repository focuses on documenting the technical methodology, analytical workflow, and machine learning techniques.

---

## 👩‍💻 Author

**Sahar Bahloul**  
Software Engineer | AI & Machine Learning
