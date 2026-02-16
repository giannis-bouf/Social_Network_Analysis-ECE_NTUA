# 🕸️ Social Network Analysis - ECE NTUA

![Course](https://img.shields.io/badge/Course-Social_Network_Analysis-blue)
![University](https://img.shields.io/badge/University-NTUA-red)
![Tools](https://img.shields.io/badge/Tools-NetworkX_/_Python-yellow)

This repository contains the laboratory projects for the **Social Network Analysis** course at the School of Electrical and Computer Engineering, **National Technical University of Athens (NTUA)**. 

The focus of this course is the study of complex network structures, community detection, and link prediction using both synthetic models and real-world datasets.

---

## 📂 Repository Structure

The repository is divided into three major laboratory units, covering different aspects of network science:

| Lab Unit | Topic | Description |
| :--- | :--- | :--- |
| **`Lab-1`** | **Complex Topologies** | Analysis of complex network topologies. Includes the study of the **web-Google** dataset (directed graph from the 2002 Google programming contest) and properties like degree distribution and shortest paths. |
| **`Lab-2`** | **Social Structure Analysis** | Community detection and social structure analysis in both artificial and real-world complex networks. Evaluation of clustering coefficients and modularity. |
| **`Lab-3`** | **Link Prediction** | Implementation of algorithms for predicting future links/connections in a network based on topological features and similarity measures. |

---

## 🧠 Key Research Areas

### 📊 Network Topologies & Large Datasets
Analysis of massive graphs, such as the **web-Google.txt**, which represents a directed web graph. We examine power-law distributions, the "small-world" phenomenon, and the robustness of the network.



### 👥 Community Detection
Identification of densely connected groups of nodes (communities) within larger networks. Application of algorithms like Louvain or Girvan-Newman to uncover hidden social structures.



### 🔗 Link Prediction
Using structural properties (Common Neighbors, Jaccard Coefficient, Adamic-Adar) to predict potential edges between nodes that are not currently connected.

---

## 🛠️ Tools & Libraries

The analysis is primarily performed using:
* **Python 3.x**
* **NetworkX:** For graph creation and manipulation.
* **Matplotlib / Seaborn:** For visualizing network properties and distributions.
* **Pandas / NumPy:** For efficient data handling.
