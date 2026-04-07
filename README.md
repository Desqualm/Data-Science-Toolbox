# Data-Science-Toolbox
A collection of advanced analytical techniques focusing on Model Explainability (XAI) and Unsupervised Learning. Includes implementations of SHAP and LIME for model auditing, alongside DBSCAN and K-Means for density-based clustering and anomaly detection.

# Data Science Toolbox: XAI, Clustering & Validation
## Core Modules

### 1. Model Validation & Selection
This module demonstrates a professional approach to verifying model stability and optimizing performance through rigorous testing.

* **`Model_Validation_Strategy_Comparison.ipynb`** – A deep dive into different validation techniques. Compares K-Fold, StratifiedKFold, and ShuffleSplit to determine the best strategy for specific data distributions.
* **`KFold_Cross_Validation_Implementation.ipynb`** – A clean, reusable implementation of the K-Fold protocol to ensure model generalizability.
* **`Random_Forest_Feature_Selection.ipynb`** – Advanced feature engineering using Random Forest to identify and select the most impactful variables, reducing model noise and complexity.

### 2. Explainable AI (XAI) & Model Auditing
Focuses on making complex machine learning decisions interpretable for business stakeholders and technical audits.

* **`XAI_LIME_vs_SHAP_Comparison.ipynb`** – A comparative study of Local (LIME) vs. Global (SHAP) explanation methods.
* **`SHAP_Classification_Analysis.ipynb`** – Application of Shapley values to interpret classification results in a healthcare/tourism context.
* **`SHAP_XGBoost_Regression_Audit.ipynb`** – Using SHAP to audit XGBoost regression models, visualizing feature impact on specific predictions.

### 3. Clustering & Anomaly Detection
Implementations of unsupervised learning for pattern recognition and outlier identification.

* **`Anomaly_Detection_DBSCAN.ipynb`** – Using density-based clustering to identify outliers and noise in spatial/weather datasets.
* **`KMeans_Clustering_Visualization.ipynb`** – Standard clustering implementation with centroid visualization and elbow-method analysis.

---

## Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Manipulation** | `Pandas`, `NumPy` |
| **Machine Learning** | `scikit-learn`, `XGBoost` |
| **Explainable AI (XAI)** | `SHAP`, `LIME` |
| **Visualization** | `Matplotlib`, `Seaborn` |
