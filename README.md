
# 🌸 Iris Flower Clustering & Classification

This project demonstrates clustering and classification techniques on the classic **Iris dataset** using `scikit-learn`. It's a beginner-friendly notebook designed for learning and visualizing clustering algorithms like **K-Means**, and optionally comparing them with classification approaches.

---

## 📌 Features

- 📊 Loads and explores the **Iris dataset**
- 🧠 Applies **K-Means clustering** & **DBScan**
- 📈 Visualizes clusters in 2D
- 🔍 (Optional) Comparison with ground truth labels for evaluation
- 🧪 Demonstrates useful toy datasets for clustering practice

---

## 🧰 Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 📁 Dataset

- **Iris Dataset**
  - Built into `sklearn.datasets`
  - 150 samples, 3 classes (`setosa`, `versicolor`, `virginica`)
  - 4 features: `sepal length`, `sepal width`, `petal length`, `petal width`

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/iris-clustering.git
   cd iris-clustering
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook irisPred.ipynb
   ```

---


## 📌 Conclusion
## 📊 Model Performance Summary

| Model / Configuration       | Silhouette Score |
|-----------------------------|------------------|
| KMeans (n_clusters=3)       | 0.6846           |
| DBSCAN                      | 0.5759           |

The KMeans algorithm achieved a higher silhouette score (0.6846) compared to DBSCAN (0.5759), indicating that KMeans formed more well-defined and cohesive clusters for the Iris dataset. 
