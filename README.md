# Myopia Clusters

Skills/Languages used: Pandas, Matplotlib, KMeans, PCA, StandardScaler, TSNE, Ploty Express, Python, Jupyter Notebook

## Instructions

This project contains four parts:

* Part 1: Prepare the Data

* Part 2: Apply Dimensionality Reduction

* Part 3: Perform a Cluster Analysis with K-means

* Part 4: Analysis

### Part 1: Prepare the Data

1. Read `myopia.csv` into a Pandas DataFrame.

2. Remove the "MYOPIC" column from the dataset.

    * **Note:** The target column is needed for supervised machine learning, but it will make an unsupervised model biased. After all, the target column is effectively providing clusters already!

3. Standardize your dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

### Part 2: Apply Dimensionality Reduction

1. Perform dimensionality reduction with PCA.

2. Further reduce the dataset dimensions with t-SNE and visually inspect the results. To do this, run t-SNE on the principal components, which is the output of the PCA transformation.

3. Create a scatter plot of the t-SNE output.

### Part 3: Perform a Cluster Analysis with K-means

Create an elbow plot to identify the best number of clusters. Make sure to:

* Use a `for` loop to determine the inertia for each `k` between 1 through 10.

### Part 4: Analysis

The project shows that the patients can be grouped into 5 clusters
