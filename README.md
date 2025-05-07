🛍️ Customer Segmentation using K-Means Clustering
This project performs unsupervised customer segmentation using K-Means Clustering on the Mall Customers dataset. 
The goal is to group customers into distinct clusters based on features like age, annual income, and spending score.

📁 Dataset
Mall_Customers.csv contains the following features:
CustomerID: Unique identifier
Gender
Age
Annual Income (k$)
Spending Score (1-100)

🧪 Tasks Performed
Load and explore the dataset
Scale/normalize numerical features
Apply PCA for 2D visualization
Use the Elbow Method to determine the optimal number of clusters
Train K-Means and assign cluster labels
Visualize clusters using scatter plot (PCA components)
Evaluate clusters using Silhouette Score

📊 Visualizations
Pairplots to understand feature relationships
Elbow plot to find optimal K
2D scatter plot of clusters using PCA

📈 Evaluation
Inertia (WCSS): Helps decide number of clusters
Silhouette Score: Measures cluster cohesion and separation

🔧 Requirements
pandas
matplotlib
seaborn
sklearn
