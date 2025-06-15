# MSCS634Lab3 - Clustering with the Wine Dataset

**Name:** Avinna Bhattarai  
**Course:** MSCS 634 - Big Data and Data Mining  
**Lab Assignment:** Lab 3 - Clustering Analysis  

##  Purpose

The purpose of this lab was to explore clustering techniques using the Wine dataset from the `sklearn` library. Both **K-Means** and **K-Medoids** algorithms were implemented to group the wine samples into clusters and evaluate clustering effectiveness using the **Silhouette Score** and **Adjusted Rand Index (ARI)**.

---

##  Key Insights

- **K-Means** achieved 0.2848589191898987 Silhouette Score and 0.8974949815093207 Adjusted Rand Index.
- **K-Medoids** achieved 0.26597740204536796 Silhouette Score and 0.7263406645756675 Adjusted Rand Index.
- PCA-based visualizations showed how each clustering method grouped the data.
- K-Medoids proved to be slightly more robust in capturing complex cluster shapes, while K-Means was faster and produced tighter groupings.

---

##  Challenges & Decisions

- Installing and using the `scikit-learn-extra` library was necessary for K-Medoids.
- Choosing the right number of clusters (k=3) aligned with the dataset's known class structure.
- Z-score normalization was applied to ensure fair comparison across features.
- PCA was used to visualize high-dimensional clustering in 2D space.

---

##  Files Included

- `Lab3_Clustering.ipynb`: Jupyter Notebook containing code and output.
- `README.md`: This file.
- `screenshots/`: Folder containing all required screenshots for clustering results and evaluations.
