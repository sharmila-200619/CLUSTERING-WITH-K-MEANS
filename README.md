# CLUSTERING-WITH-K-MEANS
TASK : 8 CLUSTERING WITH K-MEANS

# 🚢 Titanic K-Means Clustering

This project applies *unsupervised learning* to the Titanic dataset using *K-Means clustering*, with preprocessing, dimensionality reduction, optimal k selection, and visualization.

---

## 📌 Objectives

1. *Load & preprocess* the Titanic dataset  
2. *Fit K-Means* and assign cluster labels  
3. *Find optimal k* using the Elbow Method and Silhouette Score  
4. *Visualize clusters* in 2D using PCA  
5. *Evaluate clustering* quality with Silhouette Score

---

## 🗂️ Folder Structure

project/  
├── titanic_kmeans.py                  # Full clustering pipeline script  
├── README.md                          # This file  
└── titanic.csv (optional)            # Or loaded via Seaborn/Kaggle

---

## 📊 Dataset Description

You can use the *Titanic dataset* from:

- seaborn.load_dataset("titanic") (default, if online)  
- CSV from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data) (offline use)

### Features Used:
- pclass – Ticket class  
- sex – Gender  
- age – Passenger age  
- sibsp – Siblings/spouses aboard  
- parch – Parents/children aboard  
- fare – Ticket fare  
- embarked – Port of embarkation

---

## ⚙️ Tools & Libraries Used

- Python 3  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

All libraries are available by default in *Jupyter, **Colab*, or any Python environment.

---

## ✅ Task Breakdown

### Step 1 – Load & Preprocess
- Load Titanic dataset  
- Impute missing values  
- One-hot encode categorical variables  
- Standard scale numerical features

### Step 2 – Fit K-Means
- Train KMeans for values of k from 2 to 10  
- Assign cluster labels

### Step 3 – Determine Optimal k
- Plot *Elbow Curve* (Inertia vs k)  
- Plot *Silhouette Score* vs k  
- Choose best k with highest silhouette score

### Step 4 – Visualize Clusters
- Reduce dimensions using *PCA (2D)*  
- Plot clusters color-coded by labels

### Step 5 – Evaluate
- Compute final *Silhouette Score*  
- Assess cluster separation and cohesion

---

## 🚀 How to Run

1. Make sure required libraries are installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

2. Run the titanic_kmeans.py script:



python titanic_kmeans.py

3. Review plots and final silhouette score in the output.




---

📈 Sample Outputs

Elbow Curve (k vs Inertia)

Silhouette Score Plot

PCA Scatter Plot (2D clusters)

Final Silhouette Score printed in console



---

📬 Author

Sharmila L.
Machine Learning Project – July 2025 """

