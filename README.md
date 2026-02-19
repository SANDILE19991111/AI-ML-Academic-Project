# 🧠 AI/ML Academic Project Portfolio

<div align="center">
  
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange?logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.21+-green?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-red?logo=python&logoColor=white)
![Teachable Machine](https://img.shields.io/badge/Teachable%20Machine-Google-blue?logo=google&logoColor=white)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

**Bongimusa Sandile Khoza** | **Student ID: 32462409**  
**North-West University | CMPG 313 - Artificial Intelligence**

[📧 Email](mailto:bongimusakhoza@outlook.com) • [🔗 LinkedIn](https://linkedin.com/in/bongimusa-khoza-7661aa396) • [💻 GitHub](https://github.com/SANDILE19991111)

</div>

---

## 📋 Table of Contents
- [About](#-about)
- [Projects Overview](#-projects-overview)
- [Project Details](#-project-details)
  - [1. Clustering Fitness Tracker Data](#1-clustering-fitness-tracker-data)
  - [2. Teachable Machine Clothing Classifier](#2-teachable-machine-clothing-classifier)
  - [3. Clustering Random Data](#3-clustering-random-data)
  - [4. Search Algorithms - Theory Assignments](#4-search-algorithms---theory-assignments)
- [Skills & Technologies](#-skills--technologies)
- [Getting Started](#-getting-started)
- [Contact](#-contact)

---

## 📌 About

This repository contains academic projects completed for **CMPG 313 (Artificial Intelligence)** and related modules at North-West University. Each project demonstrates practical applications of machine learning and artificial intelligence concepts, from clustering algorithms to neural network classification.

**Computer Science and Mathematics graduate** with demonstrated expertise in:
- ✅ **Unsupervised Learning** - KMeans clustering on real-world inspired datasets
- ✅ **Supervised Learning** - Image classification using Google Teachable Machine
- ✅ **Search Algorithms** - BFS and Iterative Deepening DFS implementations
- ✅ **Data Analysis** - Visualization and interpretation of results
- ✅ **Synthetic Data Generation** - Creating controlled datasets for algorithm testing

---

## 📊 Projects Overview

| # | Project | Files | Key Achievement |
|---|---------|-------|-----------------|
| 1 | **🏃 Fitness Tracker Clustering** | `Clustering Fitness Tracker Data Report.pdf`<br>`3rd Practical Assignment Clustering Fitness Tracker Data.pdf` | Identified 3 distinct user groups with 0.3440 Adjusted Rand Index |
| 2 | **👕 Teachable Machine Classifier** | `1st Practical Assignment Teachable machine 2025.pdf`<br>`sandile.pdf` | Successfully classified shirts vs jackets with diverse training data |
| 3 | **🔢 Clustering Random Data** | `2nd Practical Assignment Clustering.pdf`<br>`Document1.pdf` | Achieved 98% accuracy on synthetic two-class data |
| 4 | **🧠 Search Algorithms** | `THEORY2.pdf`<br>`Theory_assignment_2.docx`<br>`32462409.pdf`<br>`1st Theoretical assignment.pdf` | BFS & IDDFS implementations for campus navigation |

---

## 📁 Project Details

### 1. 🏃 Clustering Fitness Tracker Data
**Files:** `Clustering Fitness Tracker Data Report.pdf`, `3rd Practical Assignment Clustering Fitness Tracker Data.pdf`

**Objective:** Apply KMeans clustering to identify distinct user groups based on activity levels (steps per day) and sleep patterns.

**Dataset:** Synthetic data for 3 user clusters:
| Cluster | Steps per Day | Hours Sleep | Description |
|---------|---------------|-------------|-------------|
| **Cluster 1** | 8,000-12,000 | 7-9 hours | Active users |
| **Cluster 2** | 5,000-8,000 | 6-7.5 hours | Moderately active |
| **Cluster 3** | 2,000-5,000 | 5-6.5 hours | Least active |

**Results:**
| Cluster | Avg Steps | Avg Sleep | Users |
|---------|-----------|-----------|-------|
| Cluster 1 | 8,368 | 7.0 hrs | 150 |
| Cluster 2 | 4,416 | 6.0 hrs | 200 |
| Cluster 3 | 437 | 8.0 hrs | 180 |

**Key Metrics:**
- **Adjusted Rand Index:** 0.3440 (good alignment with true clusters)
- **Key insight:** Positive correlation between physical activity and sleep duration

---

### 2. 👕 Teachable Machine Clothing Classifier
**Files:** `1st Practical Assignment Teachable machine 2025.pdf`, `sandile.pdf`

**Objective:** Train an image classification model to distinguish between shirts and jackets using Google's Teachable Machine.

**Data Collection:**
- **Shirts:** 50+ images - various colors, styles, angles, lighting conditions
- **Jackets:** 50+ images - different materials, designs, backgrounds

**Challenges Addressed:**
| Challenge | Solution |
|-----------|----------|
| Lighting variations | Captured images in bright and dim conditions |
| Background complexity | Included both plain and complex backgrounds |
| Similar-looking items | Added edge cases (jacket-like shirts) |
| Class imbalance | Maintained 50/50 split between classes |

**Key Learnings:**
- Data diversity is crucial for model generalization
- Balanced datasets prevent bias toward one class
- Edge cases reveal model limitations
- Instant feedback from Teachable Machine accelerates learning

**Potential Applications:**
- Personal wardrobe assistant apps
- Retail inventory management
- E-commerce product categorization

---

### 3. 🔢 Clustering Random Data
**Files:** `2nd Practical Assignment Clustering.pdf`, `Document1.pdf`

**Objective:** Implement KMeans clustering on artificially generated two-class datasets and experiment with parameters to understand their effects.

**Parameters Explored:**
| Parameter | Symbol | Range Tested | Effect |
|-----------|--------|--------------|--------|
| Samples per class | N1, N2 | 100-500 | More points = denser clusters |
| Class separation | d | 0.5-3.0 | Larger d = better separation |
| Dispersion | σ | 0.2-1.0 | Smaller σ = tighter clusters |

**Results:**
- ✅ **Achieved 98% clustering accuracy** with optimal parameters (d=2.0, σ=0.5)
- ✅ Larger d values significantly improved cluster separation
- ✅ Smaller σ values created tighter, more defined clusters
- ✅ Increased sample size (N=500) produced denser visualizations

**Key Takeaway:** Parameter tuning dramatically affects clustering quality - small changes in distance (d) or dispersion (σ) can make the difference between overlapping and well-separated clusters.

---

### 4. 🧠 Search Algorithms - Theory Assignments
**Files:** `THEORY2.pdf`, `Theory_assignment_2.docx`, `32462409.pdf`, `1st Theoretical assignment.pdf`

**Objective:** Formulate and solve search problems using BFS (Breadth-First Search) and Iterative Deepening DFS.

#### Three Real-World Problems Solved:

| Problem | Description | Formulation |
|---------|-------------|-------------|
| **🏛️ Campus Navigation** | Find quickest path from main entrance to various departments | States: Campus locations<br>Goal: Reach target department |
| **📅 Event Planning** | Schedule campus events without conflicts | States: Event assignments<br>Goal: No resource conflicts |
| **📚 Library Book Retrieval** | Retrieve multiple books from different sections | States: Location + books collected<br>Goal: Collect all books |

**Search Tree Traversal:**
- **BFS:** San Luis Obispo → Austin (nodes expanded in alphabetical order)
- **Iterative Deepening DFS:** Combines DFS space efficiency with BFS completeness

---

## 🛠️ Skills & Technologies

### Programming & ML Libraries
| Category | Technologies |
|----------|--------------|
| **Languages** | Python, Java, C++, JavaScript, SQL, HTML/CSS |
| **ML/AI Libraries** | scikit-learn, NumPy, Matplotlib |
| **ML Tools** | Google Teachable Machine, Google Colab, Jupyter Notebook |
| **Algorithms** | KMeans Clustering, BFS, DFS, Iterative Deepening |

### Core Competencies
