# SmartCart-Customer-Segmentation

An end-to-end Customer Segmentation using Unsupervised Machine Learning project built with Python. The project analyzes SmartCart customer data, performs data preprocessing and feature engineering, reduces dimensionality with PCA, and applies multiple clustering techniques to identify distinct customer groups.

📌 Project Overview

The goal of this project is to understand customer behavior and discover meaningful customer segments based on attributes such as:

Income

Age

Recency

Product spending

Number of children

Education

Living arrangement

Customer tenure

The project follows a complete machine-learning workflow:

Raw Customer Data → Data Cleaning → Feature Engineering → Outlier Removal → Encoding → Scaling → PCA → Cluster Evaluation → Clustering → Customer Segment Analysis

🎯 Objectives

Clean and preprocess customer data.

Handle missing values.

Create meaningful customer-level features.

Detect and remove extreme outliers.

Convert categorical features into numerical form.

Standardize features before machine learning.

Reduce dimensionality using PCA.

Determine a suitable number of clusters using:

Elbow Method

Silhouette Score

Compare clustering approaches:

K-Means Clustering

Agglomerative (Hierarchical) Clustering

Analyze income and spending patterns across customer clusters.

🧰 Technologies & Libraries

Python

Pandas — data manipulation and preprocessing

NumPy — numerical operations

Matplotlib — visualization

Seaborn — statistical visualization

Scikit-learn — preprocessing, PCA and clustering

Kneed — automatic detection of the Elbow point

Jupyter Notebook — development environment

📂 Project Structure

SmartCart-Customer-Segmentation/
│
├── Untitled1.ipynb
├── smartcart_customers (1).csv
└── README.md

Place the CSV dataset in the same directory as the notebook before running the project.


Run the notebook from top to bottom to reproduce the preprocessing, dimensionality reduction, clustering and analysis.

📈 Results

The notebook produces:

Cleaned customer data

Engineered customer features

Correlation heatmap

PCA-based 3D representation

WCSS / Elbow plot

Silhouette score analysis

K-Means cluster visualization

Agglomerative clustering visualization

Income vs spending cluster analysis

Cluster-level summary statistics

💼 Business Applications

Customer segmentation can help an e-commerce business:

Identify high-value customers.

Design targeted marketing campaigns.

Create personalized offers.

Improve customer retention strategies.

Identify different spending behaviors.

Allocate marketing budgets more effectively.

Develop customer-specific recommendations.

🚀 Future Improvements

Possible extensions for this project include:

Add a proper train/evaluation pipeline for cluster stability.

Compare additional clustering algorithms such as DBSCAN and Gaussian Mixture Models.

Perform systematic hyperparameter evaluation.

Create detailed cluster personas.

Build an interactive dashboard using Power BI, Tableau or Streamlit.

Save the processed dataset and clustering outputs.

Add automated data validation.

Create a reusable Python pipeline instead of keeping all processing inside one notebook.

Add business KPIs and recommendations for each customer segment.

👨‍💻 Author

Dev Srivastava

This project was developed as a practical demonstration of Python, Data Analysis and Unsupervised Machine Learning skills.

If you found this project useful, consider giving the repository a ⭐ on GitHub.
