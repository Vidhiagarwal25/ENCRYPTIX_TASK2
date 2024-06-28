# README: Iris Flower Classification

# Author: VIDHI AGARWAL

# Batch: June B2

# Domain: Data Science


# Aim:<br>
The aim of this project is to develop a model that can classify iris flowers into different species based on their sepal and petal measurements.


# Libraries Used:<br>
The following important libraries were used for this project:
-numpy
-pandas
-sklearn.cluster.KMeans
-matplotlib.pyplot
-seaborn


# Dataset:<br>
1. The iris dataset was loaded using seaborn's IRIS Dataset.csv function, which contains information about iris flowers, including sepal length, sepal width, petal length, petal width, and species.


# Data Exploration and Preprocessing:<br>
1. The dataset was loaded using seaborn's IRIS Dataset.csv function as a DataFrame, and its first 5 rows were displayed using data.head().
2. The 'species' column in the DataFrame was encoded to numerical values using pd.factorize(data['species']).
3. Descriptive statistics for the dataset were displayed using data.describe().
4. Missing values in the dataset were checked using data.isna().sum().


# Data Visualization:<br>
1. 3D scatter plots were created to visualize the relationship between species, petal length, and petal width, as well as between species, sepal length, and sepal width using matplotlib.pyplot and mpl_toolkits.mplot3d.Axes3D.
2. 2D scatter plots were created to visualize the relationship between species and sepal length, as well as between species and sepal width using seaborn.scatterplot.
