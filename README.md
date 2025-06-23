# KNN Variants Benchmarking and Visualization

This project implements and compares three variants of the K-Nearest Neighbors (KNN) algorithm:
- **Naive KNN**
- **KD-Tree KNN**
- **Locality Sensitive Hashing (LSH) KNN**

## Features

- Benchmarks training & query time, memory usage for:
  - Up to 10,000 samples
  - 2–50 dimensions
- Visualizes:
  - Neighbor misses in approximate methods
  - Spatial partitions of KD-tree and LSH in 2D
- Quantifies accuracy-speed trade-offs to guide algorithm selection

## Tools and Technologies
- Python, NumPy, Matplotlib, scikit-learn, tracemalloc, time

## Details
implement and compare the following different KNN variants (see:
https://youtu.be/C9HQLyXwEw0?t=3382)
a. LSH 
b. KD-tree 
c. Naive version of KNN 
Vary dataset size $N$, number of dimensions $D$ to do training and testing time and memory
comparison for finding $K$ nearest neighbours. 
Now, in a 2d randomly generated dataset visually show how many of the $K$ closest neighbors
appx. $K$ NN methods miss out due to their approximate nature.
Also show the partitions in the 2d space. 
