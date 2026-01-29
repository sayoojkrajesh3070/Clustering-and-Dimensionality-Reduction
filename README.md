# Clustering-and-Dimensionality-Reduction
# Iris Dataset Clustering Analysis

This project demonstrates the application of unsupervised machine learning techniques—specifically **KMeans** and **Hierarchical Clustering**—to the classic Iris dataset.

## Objective
The goal is to group iris flowers into clusters based on their physical measurements (sepal length, sepal width, petal length, and petal width) without using predefined labels.

## Clustering Algorithms Used

### 1. KMeans Clustering
- **Methodology:** A centroid-based approach that partitions data into $k$ clusters by minimizing the sum of squared distances between points and their respective cluster centers.
- **Selection of K:** The "Elbow Method" was used to mathematically verify that 3 is the optimal number of clusters for this dataset.



### 2. Hierarchical Clustering
- **Methodology:** An agglomerative (bottom-up) approach that builds a tree of clusters. We used the **Ward linkage** method to minimize variance during merges.
- **Visualization:** A dendrogram was generated to visualize the hierarchical relationship between samples.



## Key Findings
- Both algorithms successfully identified three distinct groups within the data.
- The 'Setosa' species is clearly separated from the other two groups.
- 'Versicolor' and 'Virginica' show some overlap due to similarities in their biological features, which is accurately reflected in the cluster visualizations.

## Technologies Used
- **Python**
- **Google Colab**
- **Scikit-learn** (Machine Learning Library)
- **Matplotlib/Seaborn** (Visualization)

## How to Run
1. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2. Ensure you have `scikit-learn`, `pandas`, and `matplotlib` installed.
3. Run all cells to generate the visualizations.
