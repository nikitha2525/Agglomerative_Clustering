🌳 Day 35 – Hierarchical Clustering using Agglomerative Method
📌 Overview

This project focuses on implementing Hierarchical Clustering (Agglomerative Clustering) to understand how data points are grouped based on similarity. Unlike K-Means, this approach builds a cluster hierarchy, allowing better insight into relationships between data points.

🎯 Objective
Understand hierarchical clustering concepts
Visualize cluster formation using a dendrogram
Apply clustering on synthetic data
Compare clustering structure using scatter plots
📊 Dataset
Synthetic dataset generated using make_blobs() from scikit-learn
Used for clear visualization of cluster formation
🧠 Algorithm Used
🔗 Agglomerative Clustering
Bottom-up approach
Starts with individual data points
Iteratively merges closest clusters
📉 Linkage Method
Used Ward linkage (minimizes variance within clusters)
⚙️ Implementation Steps
Generate synthetic dataset using make_blobs()
Apply Agglomerative Clustering
Create a dendrogram to visualize cluster hierarchy
Determine optimal number of clusters
Assign cluster labels
Visualize clusters using scatter plot
📈 Visualizations
🌲 Dendrogram
Shows hierarchical merging of clusters
Helps identify optimal cluster count
📍 Scatter Plot
Displays clustered data points
Validates clustering structure visually
🔍 Key Insights
Hierarchical clustering reveals data relationships, not just groups
Dendrogram provides a logical way to choose clusters
Linkage method significantly affects cluster formation
Works best for small to medium datasets
⚠️ Limitations
Computationally expensive for large datasets
Sensitive to noise and outliers
Requires careful interpretation of dendrogram
🚀 Conclusion

This project demonstrates how Agglomerative Clustering can be used to explore data structure and relationships. The combination of dendrogram and scatter plot provides both analytical and visual understanding of clustering behavior.

🛠️ Tech Stack
Python
NumPy
Matplotlib
Scikit-learn
🎯 Final Takeaway

Clustering is not about grouping data —
it’s about understanding the structure hidden inside it.
