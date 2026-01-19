# Agglomerative Hierarchical Clustering Using Agglomerative Clustering Tree

## Overview
This project demonstrates **Agglomerative Hierarchical Clustering** and visualizes the clustering process using an **Agglomerative Clustering Tree**.

The algorithm starts with each data point as an individual cluster and **iteratively merges the closest clusters** until a single cluster remains.  
The tree structure helps identify the **optimal number of clusters** without guessing beforehand.

---

## What This Project Does
- Loads and preprocesses a dataset
- Applies agglomerative hierarchical clustering
- Builds an **Agglomerative Clustering Tree**
- Analyzes merge distances to decide cluster count
- Assigns cluster labels based on the chosen cut level

---

## Why Agglomerative Clustering Tree?
The clustering tree shows:
- How clusters merge step-by-step
- The distance at which each merge happens

The optimal number of clusters is chosen by:
- Cutting the tree at a height with the **largest distance gap**

Large gap = meaningful separation  
Small gap = forced clustering

No clear gap → data does not naturally form clusters.

---

## Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Scikit-learn

---
