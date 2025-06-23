# KNN Variants Benchmarking and Visualization

This project implements and compares three variants of the K-Nearest Neighbors (KNN) algorithm:
- **Naive KNN**
- **KD-Tree KNN**
- **Locality Sensitive Hashing (LSH) KNN**

## 📊 Features

- Benchmarks training & query time, memory usage for:
  - Up to 10,000 samples
  - 2–50 dimensions
- Visualizes:
  - Neighbor misses in approximate methods
  - Spatial partitions of KD-tree and LSH in 2D
- Quantifies accuracy-speed trade-offs to guide algorithm selection

## 🛠 Tools and Technologies
- Python, NumPy, Matplotlib, scikit-learn, tracemalloc, time

