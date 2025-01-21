## CSCI4700 – Data Mining

### Dataset Mining and Clustering

---

## Overview
This assignment consists of three parts, where I worked with the **Agaricus-Lepiota** mushroom dataset, a gene sequence dataset, and a toy dataset for clustering. The assignment involves frequent itemset mining, sequential pattern mining, and clustering tasks. Below are the detailed instructions and requirements for the project.

---

## Dataset Information
1. **Agaricus-Lepiota Dataset**
   - **Source:** UCI Machine Learning Repository.
   - **File Name:** `agaricus-lepiota.data`
   - **Description:** This dataset includes samples of mushrooms with various attributes. Each record contains information about the physical characteristics of a mushroom.

2. **Gene Sequence Dataset**
   - **File Name:** `sequencedb.txt`
   - **Description:** This file contains hypothetical gene sequences to perform frequent sequence mining.

3. **Toy Dataset**
   - **Generated in Code:** A dataset of 100 points in a 2D plane is created programmatically for clustering.

---

### Part 1: Condensed Itemset Representations 
- **Objective:** Implement the **GenMax** and **CHARM** algorithms for frequent maximal and closed itemset mining.
- **Instructions:**
  1. Implement both algorithms using Python.
  2. Input: `agaricus-lepiota.data`.
  3. Output format:
     ```
     maximal (closed) itemset - support
     ```
     Each itemset and its support should be displayed on a new line.
  4. Include the total number of frequent maximal and closed itemsets at the end of the output.
  5. Run your code for the following minimum support thresholds:
     - `minsup = 5000`
     - `minsup = 3000`

### Part 2: Sequence Mining
- **Objective:** Implement **PrefixSpan** algorithm for frequent sequence mining.
- **Instructions:**
  1. Implement the chosen algorithm using Python.
  2. Input: `sequencedb.txt`.
  3. Output format:
     ```
     sequence - support
     ```
     Each sequence and its support should be displayed on a new line.
  4. Include the total number of frequent sequences at the end of the output.
  5. Choose a reasonable `minsup` value and document it in your code.

### Part 3: Clustering
- **Objective:** Perform **Agglomerative Hierarchical Clustering** on a toy dataset of 100 instances.
- **Instructions:**
  1. Generate a toy dataset of 100 points distributed across a 2D plane with varying densities.
  2. Use the **Euclidean distance** as the between-points distance measure.
  3. Use the **Single Link** method as the between-clusters distance measure.
  4. Visualize the resulting dendrogram using Python visualization libraries (Matplotlib, SciPy).

---

## Project Dependencies
The following Python libraries are recommended for the assignment:
- **NumPy**: For numerical computations.
- **Pandas**: For dataset handling and preprocessing.
- **Matplotlib**: For visualizing clustering results.
- **SciPy**: For dendrogram generation in clustering.

---
