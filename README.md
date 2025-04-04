📊 Customer Segmentation using DBSCAN & HDBSCAN
🚀 Overview
This project applies density-based clustering techniques (DBSCAN & HDBSCAN) to segment customers based on their Annual Income and Spending Score. Unlike traditional clustering methods, DBSCAN and HDBSCAN can detect arbitrarily shaped clusters and outliers without specifying the number of clusters beforehand.

📌 Dataset
The dataset contains simulated customer data with:

Annual Income ($)

Spending Score (1-100)

🔬 Clustering Methods Used
Clustering Algorithm	Key Features
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)	Identifies clusters based on point density and detects outliers.
HDBSCAN (Hierarchical DBSCAN)	An improved version of DBSCAN that adapts to different densities automatically.
🏗️ Project Workflow
1️⃣ Data Preprocessing
✔ Standard Scaling is applied to normalize the dataset for optimal clustering results.

2️⃣ Clustering Techniques
✔ DBSCAN is applied with eps=0.5 and min_samples=5
✔ HDBSCAN is used with min_cluster_size=5 for adaptive density-based clustering

3️⃣ Visualization & Analysis
✔ Cluster results are visualized using scatter plots
✔ Cluster counts are printed for comparison

📊 Results & Visualizations
🔹 DBSCAN Clustering
Detects core points, border points, and noise points.

Outliers are labeled as -1.

🔹 HDBSCAN Clustering
Adapts to varying cluster densities, making it more flexible than DBSCAN.

Can return noisy points (-1) and soft clustering scores.

🎯 Key Takeaways
✅ Understanding of density-based clustering
✅ Comparison between DBSCAN & HDBSCAN
✅ Identification of outliers & noise points
✅ Practical implementation of unsupervised learning

🔮 Future Enhancements
🔹 Experiment with different distance metrics (e.g., Manhattan, Cosine)
🔹 Apply clustering on real-world customer datasets
🔹 Integrate results into business insights & marketing strategies
