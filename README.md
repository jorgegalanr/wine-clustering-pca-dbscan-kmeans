# 🍷 Wine Clustering & PCA with K-Means and DBSCAN

## 📌 Description
Unsupervised learning project applied to the **Wine Quality dataset** (red and white wines).  
The goal is to analyze chemical properties, detect outliers, reduce dimensionality with **PCA**, and group wines using **K-Means** and **DBSCAN** clustering.

---

## 🎯 Objectives
- Perform **EDA** (exploratory data analysis) and detect outliers.  
- Explore correlations among wine features.  
- Apply **PCA** for dimensionality reduction.  
- Compare clustering methods: **K-Means** vs **DBSCAN**.  
- Visualize clusters in 2D using PCA components.  

---

## 📊 Dataset
Wine Quality dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).  
- Red wines: 1,599 samples  
- White wines: 4,898 samples  
- 11 chemical properties (acidity, pH, sugars, alcohol, sulphates, etc.)

---

## ⚙️ Tech Stack
- **Python**  
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn  
- **Notebook:** Jupyter  

---

## 🔎 Methodology
1. **Data Preprocessing**  
   - Check null values, duplicates, ranges.  
   - Normalize variables for PCA.  

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics (mean, std, percentiles).  
   - Boxplots for outliers.  
   - Correlation heatmap.  

3. **Dimensionality Reduction**  
   - Apply PCA to reduce 11 features to 2 components (>70% variance explained).  

4. **Clustering**  
   - Run **K-Means** with elbow method.  
   - Run **DBSCAN** with Silhouette & Calinski-Harabasz evaluation.  

5. **Visualization**  
   - 2D PCA scatter plots with clusters highlighted.  

---

## 📈 Results
- PCA reduced dimensionality while preserving relevant variance.  
- **K-Means** grouped wines into 4 clusters (whites) and 5 clusters (reds).  
- **DBSCAN** detected outliers that K-Means misclassified.

## Results (Versión en Español)
- PCA redujo de 11 variables a 2 componentes (<70% varianza).
- K-Means identificó entre 4 y 5 clusters principales.
- DBSCAN detectó vinos con características atípicas (outliers).

---

## 🚀 How to Run
```bash
git clone https://github.com/jorgegalanr/wine-clustering-pca-dbscan-kmeans.git
cd wine-clustering-pca-dbscan-kmeans
pip install -r requirements.txt
jupyter notebook notebooks/wine_analysis.ipynb
```



