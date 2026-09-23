# Data Mining Textbook

> A comprehensive course textbook for **Data Mining**, provided in Jupyter Notebook and PDF formats.

[![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Format](https://img.shields.io/badge/Format-Jupyter%20Notebook%20%7C%20PDF-orange.svg)](https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes)
[![Semester](https://img.shields.io/badge/Semester-Fall%202026-blue.svg)](https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes)

# [توضیحات فارسی](https://github.com/hrnrxb/Data-Mining-Textbook/blob/main/README_FA.md)


---

## At a Glance

**Data Mining Textbook — Version 2** is a comprehensive, Persian-language textbook for the **Data Mining** course at **Islamic Azad University, Shiraz Branch, Faculty of Computer Engineering**, prepared for **Fall 2026 (2026–2027 academic year)**. It is provided in both **Jupyter Notebook** and **PDF** formats and combines conceptual explanations, mathematical formulations, examples, visualizations, and executable Python demonstrations.

This edition is a substantially redesigned and expanded successor to **[Version 1](https://github.com/hrnrxb/Data_Mining_Fall2025)**. The Version 2 textbook has been prepared and provided as course material for the university's Data Mining course in **Fall 2026**.

[Data Mining Course Page (Fall 2026)](https://iau-shiraz-courses.github.io/DM-fall2026/)
---

# Table of Contents

- [Overview](#overview)
- [Project Lineage](#project-lineage)
- [Current Release](#current-release)
- [Course Information](#course-information)
- [Instructor](#instructor)
- [Authors and Design Team](#authors-and-design-team)
- [Repository Statistics](#repository-statistics)
- [Repository Structure](#repository-structure)
- [Chapter 01 – Introduction](#chapter-01--introduction)
- [Chapter 02 – Data, Measurements, and Data Preprocessing](#chapter-02--data-measurements-and-data-preprocessing)
- [Chapter 03 – Data Warehousing and Online Analytical Processing](#chapter-03--data-warehousing-and-online-analytical-processing)
- [Chapter 04 – Pattern Mining: Basic Concepts and Methods](#chapter-04--pattern-mining-basic-concepts-and-methods)
- [Chapter 05 – Advanced Pattern Mining](#chapter-05--advanced-pattern-mining)
- [Chapter 06 – Classification: Basic Concepts and Techniques](#chapter-06--classification-basic-concepts-and-techniques)
- [Chapter 07 – Classification: Advanced Methods](#chapter-07--classification-advanced-methods)
- [Chapter 08 – Cluster Analysis](#chapter-08--cluster-analysis)
- [Chapter 09 – Planned / In Progress](#chapter-09--planned--in-progress)
- [Chapter 10 – Deep Learning](#chapter-10--deep-learning)
- [Chapter 11 – Planned / In Progress](#chapter-11--planned--in-progress)
- [Chapter 12 – Data Mining Trends and Research Frontiers](#chapter-12--data-mining-trends-and-research-frontiers)
- [Learning Approach](#learning-approach)
- [Notebook Format](#notebook-format)
- [PDF Format](#pdf-format)
- [Running the Notebooks](#running-the-notebooks)
- [Python Dependencies](#python-dependencies)
- [Chapter-Level Dependency Overview](#chapter-level-dependency-overview)
- [Python Version Information](#python-version-information)
- [Images and External Assets](#images-and-external-assets)
- [License](#license)
- [Copyright and Third-Party Material](#copyright-and-third-party-material)
- [Citation](#citation)
- [Repository and GitHub](#repository-and-github)
- [Recommended Git Hygiene](#recommended-git-hygiene)
- [Release Philosophy](#release-philosophy)
- [Future Releases](#future-releases)
- [Quality and Accuracy](#quality-and-accuracy)
- [Contribution and Issue Reporting](#contribution-and-issue-reporting)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Contact and Permissions](#contact-and-permissions)
- [Acknowledgment](#acknowledgment)

---
## Overview

This repository contains the current public release of the **Data Mining** course textbook prepared for **Fall 2026**, corresponding to the **2026–2027 academic year**, at **Islamic Azad University, Shiraz Branch – Faculty of Computer Engineering**.

The textbook are provided in two synchronized formats:

- **Jupyter Notebook (`.ipynb`)** for interactive reading, mathematical notation, executable Python cells, visualizations, examples, and demonstrations.
- **PDF (`.pdf`)** for linear reading, offline study, printing, annotation, and archival use.

The notebooks are the primary interactive source of the textbook, while the PDFs provide a stable reading-oriented representation of the corresponding chapters.

The project is intended to be more than a compact list of definitions. Its structure combines conceptual explanations, intuition, mathematical formulations, examples, diagrams, visualizations, implementation-oriented demonstrations, and practical context throughout the published chapters.

---

# Project Lineage

## Version 2 of the Course Textbook

This repository is the **second version** of an earlier Data Mining course textbook project.

Although this release is formally a **Version 2**, it should not be understood as a minor revision or a simple continuation of the previous notes.

The second version has been **substantially redesigned, rewritten, reorganized, expanded, and reworked**.

Large portions of the material have been revisited from the ground up, including the structure of explanations, presentation of concepts, mathematical treatment, examples, visual elements, notebook organization, and practical demonstrations.

As a result, Version 2 should be regarded as a **new and substantially reworked edition** of the course textbook rather than merely an edited copy of Version 1.

The relationship can therefore be summarized as:

```text
Version 1
   │
   │  Major restructuring, rewriting,
   │  expansion, redesign, and reworking
   ▼
Version 2
```

Version 1 is the conceptual predecessor of this project, but the textbook published here represents the current Version 2 release.

---

# Current Release

The current public release contains the following completed chapters:

| Chapter | Status | Notebook | PDF |
|---|---|---|---|
| 01 | Published | `01/ch01.ipynb` | `01/ch01.pdf` |
| 02 | Published | `02/ch02.ipynb` | `02/ch02.pdf` |
| 03 | Published | `03/ch03.ipynb` | `03/ch03.pdf` |
| 04 | Published | `04/ch04.ipynb` | `04/ch04.pdf` |
| 05 | Published | `05/ch05.ipynb` | `05/ch05.pdf` |
| 06 | Published | `06/ch06.ipynb` | `06/ch06.pdf` |
| 07 | Published | `07/ch07.ipynb` | `07/ch07.pdf` |
| 08 | Published | `08/ch08.ipynb` | `08/ch08.pdf` |
| 09 | In progress / not published | — | — |
| 10 | Published | `10/ch10.ipynb` | `10/ch10.pdf` |
| 11 | In progress / not published | — | — |
| 12 | Published | `12/ch12.ipynb` | `12/ch12.pdf` |

### Chapters 09 and 11

Chapters **09** and **11** are part of the broader Version 2 course textbook project but are still under development.

They are intentionally excluded from the current public release.

They will be added to the repository after their material has been completed and prepared for publication.

Their absence from the current release is therefore intentional and should not be interpreted as an error or omission in the course structure.

---

# Course Information

| Field | Information |
|---|---|
| Course | Data Mining |
| University | Islamic Azad University, Shiraz Branch |
| Faculty | Faculty of Computer Engineering |
| Semester | Fall 2026 |
| Academic Year | 2026–2027 |
| Instructor | [Dr. Amin Eskandari](https://ir.linkedin.com/in/amin-eskandari-1756a73b) |
| Primary Language | Persian |
| Technical Terminology | English terminology with Persian explanations |
| Interactive Format | Jupyter Notebook |
| Reading / Print Format | PDF |
| Edition | Version 2 |

---

# Instructor

## [Dr. Amin Eskandari](https://ir.linkedin.com/in/amin-eskandari-1756a73b)

**Course Instructor**

The instructor listed in the course material is:

[**Dr. Amin Eskandari**](https://ir.linkedin.com/in/amin-eskandari-1756a73b)

---

# Authors and Design Team

The following members are identified in the course material as the design team responsible for preparing and organizing the textbook:

1. [**Hamid Namjoo**](https://hamidnamjoo.com/)
2. [**Amir Hossein Hemmati**](https://github.com/AmirHosseinHemati)
3. [**AmirMohammad Asadjoo**](https://github.com/Amir-Mohammd-Asadjoo)
4. **Ali Nikvan**
5. **Reza Liaqat**
6. **Alireza Moghaddas**
7. **Golnoush Hosseinpour**
8. **Elham Izadi**

> The names above follow the English transliterations used for the repository documentation. Official author-preferred spellings can be adopted in a future release if the authors provide them.

---

# Repository Statistics

The current public release contains:

- **10 published chapters**
- **10 Jupyter Notebook files**
- **10 PDF files**
- **1,293 PDF pages in total**
- **1,095 Notebook cells**
- **832 Markdown cells**
- **263 code cells**
- Approximately **51,406 lines of code** across the code cells of the published notebooks
- **227 local image files**

These statistics describe the current public release and may change as the repository evolves.

## Notebook Statistics by Chapter

| Chapter | Total Cells | Markdown Cells | Code Cells | PDF Pages |
|---:|---:|---:|---:|---:|
| 01 | 104 | 81 | 23 | 97 |
| 02 | 208 | 162 | 46 | 163 |
| 03 | 117 | 95 | 22 | 116 |
| 04 | 84 | 70 | 14 | 86 |
| 05 | 74 | 53 | 21 | 119 |
| 06 | 118 | 82 | 36 | 186 |
| 07 | 121 | 92 | 29 | 183 |
| 08 | 79 | 56 | 23 | 115 |
| 10 | 83 | 65 | 18 | 108 |
| 12 | 107 | 76 | 31 | 120 |
| **Total** | **1,095** | **832** | **263** | **1,293** |

---

# Repository Structure

The intended public structure is:

```text
data-mining-notes/
│
├── README.md
├── LICENSE
│
├── 01/
│   ├── ch01.ipynb
│   ├── ch01.pdf
│   └── src/
│       └── images/
│
├── 02/
│   ├── ch02.ipynb
│   ├── ch02.pdf
│   └── src/
│       └── images/
│
├── 03/
│   ├── ch03.ipynb
│   ├── ch03.pdf
│   └── src/
│       └── images/
│
├── 04/
│   ├── ch04.ipynb
│   ├── ch04.pdf
│   └── src/
│       └── images/
│
├── 05/
│   ├── ch05.ipynb
│   ├── ch05.pdf
│   └── src/
│       └── images/
│
├── 06/
│   ├── ch06.ipynb
│   ├── ch06.pdf
│   └── src/
│       └── images/
│
├── 07/
│   ├── ch07.ipynb
│   ├── ch07.pdf
│   └── src/
│       └── images/
│
├── 08/
│   ├── ch08.ipynb
│   ├── ch08.pdf
│   └── src/
│       └── images/
│
├── 10/
│   ├── ch10.ipynb
│   ├── ch10.pdf
│   └── src/
│       └── images/
│
└── 12/
    ├── ch12.ipynb
    ├── ch12.pdf
    └── src/
        └── images/
```

Development metadata and temporary notebook directories should not be committed to the public repository.

Recommended exclusions include:

```text
.git/
.ipynb_checkpoints/
```

---

# Chapter 01 – Introduction

**Files**

- [`01/ch01.ipynb`](./01/ch01.ipynb)
- [`01/ch01.pdf`](./01/ch01.pdf)

**PDF length:** 97 pages

## Topics

### 1.1 What is Data Mining?

### 1.2 Data Mining: An Essential Step in Knowledge Discovery

### 1.3 Diversity of Data Types for Data Mining

### 1.4 Mining Various Kinds of Knowledge

- 1.4.1 Multidimensional data summarization
- 1.4.2 Mining frequent patterns, associations, and correlations
- 1.4.3 Classification and regression for predictive analysis
- 1.4.4 Cluster analysis
- 1.4.5 Deep learning
- 1.4.6 Outlier analysis
- 1.4.7 Are all mining results interesting?

### 1.5 Data Mining: Confluence of Multiple Disciplines

- 1.5.1 Statistics and data mining
- 1.5.2 Machine learning and data mining
- 1.5.3 Database technology and data mining
- 1.5.4 Data mining and data science
- 1.5.5 Data mining and other disciplines

### 1.6 Data Mining and Applications

### 1.7 Data Mining and Society

## Chapter Focus

Chapter 1 establishes the conceptual foundation of data mining.

It introduces the role of data mining within knowledge discovery, surveys major data types and mining tasks, and discusses the relationship between data mining and fields such as statistics, machine learning, database technology, and data science.

---

# Chapter 02 – Data, Measurements, and Data Preprocessing

**Files**

- [`02/ch02.ipynb`](./02/ch02.ipynb)
- [`02/ch02.pdf`](./02/ch02.pdf)

**PDF length:** 163 pages

## Topics

### 2.1 Data Types

- 2.1.1 Nominal attributes
- 2.1.2 Binary attributes
- 2.1.3 Ordinal attributes
- 2.1.4 Numeric attributes
- 2.1.5 Discrete vs. continuous attributes

### 2.2 Statistics of Data

- 2.2.1 Measuring the central tendency
- 2.2.2 Measuring the dispersion of data
- 2.2.3 Covariance and correlation analysis
- 2.2.4 Graphic displays of basic statistics of data

### 2.3 Similarity and Distance Measures

- 2.3.1 Data matrix vs. dissimilarity matrix
- 2.3.2 Proximity measures for nominal attributes
- 2.3.3 Proximity measures for binary attributes
- 2.3.4 Dissimilarity of numeric data: Minkowski distance
- 2.3.5 Proximity measures for ordinal attributes
- 2.3.6 Dissimilarity for attributes of mixed types
- 2.3.7 Cosine similarity
- 2.3.8 Measuring similar distributions: the Kullback–Leibler divergence
- 2.3.9 Capturing hidden semantics in similarity measures

### 2.4 Data Quality, Data Cleaning, and Data Integration

- 2.4.1 Data quality measures
- 2.4.2 Data cleaning
- 2.4.3 Data integration

### 2.5 Data Transformation

- 2.5.1 Normalization
- 2.5.2 Discretization
- 2.5.3 Data compression
- 2.5.4 Sampling

### 2.6 Dimensionality Reduction

- 2.6.1 Principal components analysis
- 2.6.2 Attribute subset selection
- 2.6.3 Nonlinear dimensionality reduction methods

## Chapter Focus

Chapter 2 develops the foundations required to work with data in practical data-mining systems.

It begins with data and attribute types, proceeds through descriptive statistics and similarity measures, and then addresses data quality, cleaning, integration, transformation, normalization, discretization, compression, sampling, and dimensionality reduction.

---

# Chapter 03 – Data Warehousing and Online Analytical Processing

**Files**

- [`03/ch03.ipynb`](./03/ch03.ipynb)
- [`03/ch03.pdf`](./03/ch03.pdf)

**PDF length:** 116 pages

## Topics

### 3.1 Data Warehouse

- 3.1.1 Data warehouse: what and why?
- 3.1.2 Architecture of data warehouses: enterprise data warehouses and data marts
- 3.1.3 Data lakes

### 3.2 Data Warehouse Modeling: Schema and Measures

- 3.2.1 Data cube: a multidimensional data model
- 3.2.2 Schemas for multidimensional data models: stars, snowflakes, and fact constellations
- 3.2.3 Concept hierarchies
- 3.2.4 Measures: categorization and computation

### 3.3 OLAP Operations

- 3.3.1 Typical OLAP operations
- 3.3.2 Indexing OLAP data: bitmap index and join index
- 3.3.3 Storage implementation: column-based databases

### 3.4 Data Cube Computation

- 3.4.1 Terminology of data cube computation
- 3.4.2 Data cube materialization: ideas
- 3.4.3 OLAP server architectures: ROLAP vs. MOLAP vs. HOLAP
- 3.4.4 General strategies for data cube computation

### 3.5 Data Cube Computation Methods

- 3.5.1 Multiway array aggregation for full cube computation
- 3.5.2 BUC: computing iceberg cubes from the apex cuboid downward
- 3.5.3 Precomputing shell fragments for fast high-dimensional OLAP
- 3.5.4 Efficient processing of OLAP queries using cuboids

## Chapter Focus

Chapter 3 focuses on the analytical infrastructure surrounding data mining, including data warehouses, data marts, data lakes, multidimensional data models, data cubes, concept hierarchies, OLAP operations, indexing strategies, storage approaches, and data cube computation.

---

# Chapter 04 – Pattern Mining: Basic Concepts and Methods

**Files**

- [`04/ch04.ipynb`](./04/ch04.ipynb)
- [`04/ch04.pdf`](./04/ch04.pdf)

**PDF length:** 86 pages

## Topics

### 4.1 Basic Concepts

- 4.1.1 Market basket analysis: a motivating example
- 4.1.2 Frequent itemsets, closed itemsets, and association rules

### 4.2 Frequent Itemset Mining Methods

- 4.2.1 Apriori algorithm: finding frequent itemsets by confined candidate generation
- 4.2.2 Generating association rules from frequent itemsets
- 4.2.3 Improving the efficiency of Apriori
- 4.2.4 A pattern-growth approach for mining frequent itemsets
- 4.2.5 Mining frequent itemsets using the vertical data format
- 4.2.6 Mining closed and max patterns

### 4.3 Which Patterns Are Interesting? Pattern Evaluation Methods

- 4.3.1 Strong rules are not necessarily interesting
- 4.3.2 From association analysis to correlation analysis
- 4.3.3 A comparison of pattern evaluation measures

## Chapter Focus

Chapter 4 introduces frequent-pattern mining and association analysis, progressing from the market-basket perspective to frequent itemsets, association rules, Apriori, pattern-growth methods, vertical representations, closed and maximal patterns, and pattern-evaluation measures.

---

# Chapter 05 – Advanced Pattern Mining

**Files**

- [`05/ch05.ipynb`](./05/ch05.ipynb)
- [`05/ch05.pdf`](./05/ch05.pdf)

**PDF length:** 119 pages

## Topics

### 5.1 Mining Various Kinds of Patterns

- 5.1.1 Mining multilevel associations
- 5.1.2 Mining multidimensional associations
- 5.1.3 Mining quantitative association rules
- 5.1.4 Mining high-dimensional data
- 5.1.5 Mining rare patterns and negative patterns

### 5.2 Mining Compressed or Approximate Patterns

- 5.2.1 Mining compressed patterns by pattern clustering
- 5.2.2 Extracting redundancy-aware top-k patterns

### 5.3 Constraint-Based Pattern Mining

- 5.3.1 Pruning pattern space with pattern pruning constraints
- 5.3.2 Pruning data space with data pruning constraints
- 5.3.3 Mining space pruning with succinctness constraints

### 5.4 Mining Sequential Patterns

- 5.4.1 Sequential pattern mining: concepts and primitives
- 5.4.2 Scalable methods for mining sequential patterns
- 5.4.3 Constraint-based mining of sequential patterns

### 5.5 Mining Subgraph Patterns

- 5.5.1 Methods for mining frequent subgraphs
- 5.5.2 Mining variant and constrained substructure patterns

### 5.6 Pattern Mining: Application Examples

- 5.6.1 Phrase mining in massive text data
- 5.6.2 Mining copy and paste bugs in software programs

## Chapter Focus

Chapter 5 extends pattern mining to more complex structures and constraints, including multilevel and multidimensional associations, quantitative and high-dimensional patterns, rare and negative patterns, compressed and approximate patterns, top-k patterns, constraint-based mining, sequential patterns, and subgraph patterns.

---

# Chapter 06 – Classification: Basic Concepts and Techniques

**Files**

- [`06/ch06.ipynb`](./06/ch06.ipynb)
- [`06/ch06.pdf`](./06/ch06.pdf)

**PDF length:** 186 pages

## Topics

### 6.1 Basic Concepts

- 6.1.1 What is classification?
- 6.1.2 General approach to classification

### 6.2 Decision Tree Induction

- 6.2.1 Decision tree induction
- 6.2.2 Attribute selection measures
- 6.2.3 Tree pruning

### 6.3 Bayes Classification Methods

- 6.3.1 Bayes' theorem
- 6.3.2 Naive Bayesian classification

### 6.4 Lazy Learners

- 6.4.1 k-nearest-neighbor classifiers
- 6.4.2 Case-based reasoning

### 6.5 Linear Classifiers

- 6.5.1 Linear regression
- 6.5.2 Perceptron: turning linear regression to classification
- 6.5.3 Logistic regression

### 6.6 Model Evaluation and Selection

- 6.6.1 Metrics for evaluating classifier performance
- 6.6.2 Holdout method and random subsampling
- 6.6.3 Cross-validation
- 6.6.4 Bootstrap
- 6.6.5 Model selection using statistical tests of significance
- 6.6.6 Comparing classifiers based on cost–benefit and ROC curves

### 6.7 Techniques to Improve Classification Accuracy

- 6.7.1 Introducing ensemble methods
- 6.7.2 Bagging
- 6.7.3 Boosting
- 6.7.4 Random forests
- 6.7.5 Improving classification accuracy of class-imbalanced data

## Chapter Focus

Chapter 6 introduces supervised classification from fundamental models through ensemble techniques.

It covers decision trees, Bayes classifiers, k-nearest neighbors, case-based reasoning, linear and logistic models, perceptrons, evaluation and selection methods, cross-validation, bootstrap, ROC analysis, and ensemble learning.

---

# Chapter 07 – Classification: Advanced Methods

**Files**

- [`07/ch07.ipynb`](./07/ch07.ipynb)
- [`07/ch07.pdf`](./07/ch07.pdf)

**PDF length:** 183 pages

## Topics

### 7.1 Feature Selection and Engineering

- 7.1.1 Filter methods
- 7.1.2 Wrapper methods
- 7.1.3 Embedded methods

### 7.2 Bayesian Belief Networks

- 7.2.1 Concepts and mechanisms
- 7.2.2 Training Bayesian belief networks

### 7.3 Support Vector Machines

- 7.3.1 Linear support vector machines
- 7.3.2 Nonlinear support vector machines

### 7.4 Rule-Based and Pattern-Based Classification

- 7.4.1 Using IF-THEN rules for classification
- 7.4.2 Rule extraction from a decision tree
- 7.4.3 Rule induction using a sequential covering algorithm
- 7.4.4 Associative classification
- 7.4.5 Discriminative frequent pattern-based classification

### 7.5 Classification with Weak Supervision

- 7.5.1 Semisupervised classification
- 7.5.2 Active learning
- 7.5.3 Transfer learning
- 7.5.4 Distant supervision
- 7.5.5 Zero-shot learning

### 7.6 Classification with Rich Data Types

- 7.6.1 Stream data classification
- 7.6.2 Sequence classification
- 7.6.3 Graph data classification

### 7.7 Potpourri: Other Related Techniques

- 7.7.1 Multiclass classification
- 7.7.2 Distance metric learning
- 7.7.3 Interpretability of classification
- 7.7.4 Genetic algorithms
- 7.7.5 Reinforcement learning

## Chapter Focus

Chapter 7 extends classification to advanced modeling approaches, feature selection, Bayesian belief networks, SVMs, rule and pattern-based methods, weak supervision, classification over rich data types, multiclass learning, metric learning, interpretability, genetic algorithms, and reinforcement learning.

---

# Chapter 08 – Cluster Analysis

**Files**

- [`08/ch08.ipynb`](./08/ch08.ipynb)
- [`08/ch08.pdf`](./08/ch08.pdf)

**PDF length:** 115 pages

## Topics

### 8.1 Cluster Analysis

- 8.1.1 What is cluster analysis?
- 8.1.2 Requirements for cluster analysis
- 8.1.3 Overview of basic clustering methods

### 8.2 Partitioning Methods

- 8.2.1 k-Means: a centroid-based technique
- 8.2.2 Variations of k-means

### 8.3 Hierarchical Methods

- 8.3.1 Basic concepts of hierarchical clustering
- 8.3.2 Agglomerative hierarchical clustering
- 8.3.3 Divisive hierarchical clustering
- 8.3.4 BIRCH: scalable hierarchical clustering using clustering feature trees
- 8.3.5 Probabilistic hierarchical clustering

### 8.4 Density-Based and Grid-Based Methods

- 8.4.1 DBSCAN: density-based clustering based on connected regions with high density
- 8.4.2 DENCLUE: clustering based on density distribution functions
- 8.4.3 Grid-based methods

### 8.5 Evaluation of Clustering

- 8.5.1 Assessing clustering tendency
- 8.5.2 Determining the number of clusters
- 8.5.3 Measuring clustering quality: extrinsic methods
- 8.5.4 Intrinsic methods

## Chapter Focus

Chapter 8 introduces clustering as an unsupervised-learning problem and examines partitioning, hierarchical, density-based, and grid-based approaches together with methods for assessing clustering tendency, choosing cluster counts, and evaluating cluster quality.

---

# Chapter 09 – Planned / In Progress

**Status:** Not published yet.

Chapter 9 is part of Version 2 but is still under development.

It is intentionally excluded from the current public release and will be added after the material has been completed and prepared for publication.

---

# Chapter 10 – Deep Learning

**Files**

- [`10/ch10.ipynb`](./10/ch10.ipynb)
- [`10/ch10.pdf`](./10/ch10.pdf)

**PDF length:** 108 pages

## Topics

### 10.1 Basic Concepts

- 10.1.1 What is deep learning?
- 10.1.2 Backpropagation algorithm
- 10.1.3 Key challenges for training deep learning models
- 10.1.4 Overview of deep learning architecture

### 10.2 Improve Training of Deep Learning Models

- 10.2.1 Responsive activation functions
- 10.2.2 Adaptive learning rate
- 10.2.3 Dropout
- 10.2.4 Pretraining
- 10.2.5 Cross-entropy
- 10.2.6 Autoencoder: unsupervised deep learning
- 10.2.7 Other techniques

### 10.3 Convolutional Neural Networks

- 10.3.1 Introducing convolution operation
- 10.3.2 Multidimensional convolution
- 10.3.3 Convolutional layer

### 10.4 Recurrent Neural Networks

- 10.4.1 Basic RNN models and applications
- 10.4.2 Gated RNNs
- 10.4.3 Other techniques for addressing long-term dependence

### 10.5 Graph Neural Networks

- 10.5.1 Basic concepts
- 10.5.2 Graph convolutional networks
- 10.5.3 Other types of GNNs

## Chapter Focus

Chapter 10 introduces deep learning from neural-network fundamentals through modern deep architectures, covering backpropagation, training challenges, activation functions, adaptive learning, dropout, pretraining, cross-entropy, autoencoders, CNNs, RNNs, gated architectures, and GNNs.

---

# Chapter 11 – Planned / In Progress

**Status:** Not published yet.

Chapter 11 is part of Version 2 but is still under development.

It is intentionally excluded from the current public release and will be added after the material has been completed and prepared for publication.

---

# Chapter 12 – Data Mining Trends and Research Frontiers

**Files**

- [`12/ch12.ipynb`](./12/ch12.ipynb)
- [`12/ch12.pdf`](./12/ch12.pdf)

**PDF length:** 120 pages

## Topics

### 12.1 Mining Rich Data Types

- 12.1.1 Mining text data
- 12.1.2 Spatial-temporal data
- 12.1.3 Graphs and networks

### 12.2 Data Mining Applications

- 12.2.1 Data mining for sentiment and opinion
- 12.2.2 Truth discovery and misinformation identification
- 12.2.3 Information and disease propagation
- 12.2.4 Productivity and team science

### 12.3 Data Mining Methodologies and Systems

- 12.3.1 Structuring unstructured data for knowledge mining: a data-driven approach
- 12.3.2 Data augmentation
- 12.3.3 From correlation to causality
- 12.3.4 Network as a context
- 12.3.5 AutoML: methods and systems

### 12.4 Data Mining, People, and Society

- 12.4.1 Privacy-preserving data mining
- 12.4.2 Human-algorithm interaction
- 12.4.3 Mining beyond maximizing accuracy: fairness, interpretability, and robustness
- 12.4.4 Data mining for social good

## Chapter Focus

Chapter 12 moves toward current research directions and emerging application areas, including rich data types, text, spatial-temporal data, graphs and networks, sentiment and opinion mining, truth discovery, misinformation identification, propagation, data augmentation, causality, AutoML, privacy-preserving data mining, human-algorithm interaction, fairness, interpretability, robustness, and data mining for social good.

---

# Learning Approach

The textbook combine several complementary layers of learning.

## 1. Conceptual Understanding

Core concepts are presented in context rather than as isolated definitions.

## 2. Intuition

Abstract ideas are supported by explanatory descriptions and practical interpretations where appropriate.

## 3. Mathematical Formulation

When mathematical structure is central to a method, equations and formal notation are included.

## 4. Visualization

Charts, diagrams, figures, and other visual elements are used throughout the material.

## 5. Implementation

Many topics are accompanied by executable Python examples that connect theory with computation.

## 6. Application Context

Examples and scenarios are used to connect algorithms and concepts to practical data-mining settings.

---

# Notebook Format

The `.ipynb` files are the interactive form of the textbook.

They contain combinations of:

- Markdown explanations
- Mathematical notation
- Structured headings
- HTML/CSS-enhanced presentation
- Images
- Diagrams
- Python code
- Data visualizations
- Explanatory output
- Examples and demonstrations

The Notebook format keeps multiple layers of learning together:

```text
Concept
   ↓
Explanation
   ↓
Mathematical formulation
   ↓
Example
   ↓
Python implementation
   ↓
Visualization / output
```

---

# PDF Format

Each published chapter includes a corresponding PDF.

The PDF format is intended for:

- Linear reading
- Printing
- Offline study
- Annotation
- Long-form review
- Archival use

For interactive exploration and code execution, use the Notebook version.

For stable reading and printing, use the PDF version.

---

# Running the Notebooks

## Option 1 – View on GitHub

GitHub can render Jupyter Notebook files for reading.

This is useful for:

- Reading Markdown
- Inspecting equations
- Browsing code
- Viewing saved outputs
- Navigating the chapter structure

GitHub rendering does not provide a full local execution environment.

## Option 2 – Run Locally with Jupyter

Clone the repository:

```bash
git clone https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes.git
cd data-mining-notes
```

Start Jupyter Lab:

```bash
jupyter lab
```

or:

```bash
jupyter notebook
```

Open the Notebook corresponding to the chapter you want to study.

## Execution Notes

The repository is distributed as course material rather than as a fully pinned software environment.

Different chapters use different subsets of Python packages.

For reading the PDFs, no Python installation is required.

For executing code, install the dependencies required by the relevant chapter.

---

# Python Dependencies

No single locked `requirements.txt` is currently provided for all chapters.

The following libraries appear across the published notebooks.

## Scientific Computing and Data Analysis

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`

## Machine Learning

- `scikit-learn`

## Graph and Network Analysis

- `networkx`

## Natural Language Processing

- `nltk`
- `gensim`
- `textblob`

## Pattern Mining

- `mlxtend`

## Geometry and Spatial Processing

- `shapely`

## Image Processing

- `scikit-image`

## Notebook / Interactive Computing

- `IPython`
- Jupyter environment components

## Standard Python Library

The notebooks also use standard-library modules where appropriate, including:

- `re`
- `math`
- `collections`
- `itertools`
- `time`
- `warnings`
- `os`
- `json`
- `sqlite3`
- `zipfile`
- `urllib`

The exact dependency set depends on the chapter and on which cells the reader chooses to execute.

---

# Chapter-Level Dependency Overview

## Chapter 01

```text
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn
networkx
mlxtend
```

## Chapter 02

```text
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn
gensim
```

## Chapter 03

```text
numpy
pandas
matplotlib
seaborn
```

## Chapter 04

```text
numpy
pandas
matplotlib
seaborn
mlxtend
```

## Chapter 05

```text
numpy
pandas
matplotlib
seaborn
gensim
nltk
```

## Chapter 06

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
```

## Chapter 07

```text
numpy
pandas
matplotlib
seaborn
```

## Chapter 08

```text
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn
```

## Chapter 10

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
```

## Chapter 12

```text
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn
networkx
shapely
scikit-image
textblob
```

---

# Python Version Information

Metadata in the current notebooks shows that the material has been created or edited in multiple Python 3 environments, including:

- Python 3.12.5
- Python 3.13.5
- Python 3.13.7

The repository should therefore be treated as course material rather than as a software project with a single locked interpreter version.

---

# Images and External Assets

Each published chapter contains a local:

```text
src/images/
```

directory.

These images are referenced by the Notebook files and are included so that the visual presentation can be reproduced when the repository is viewed or run locally.

The current public release contains **227 local image files**.

## Third-Party Image Notice

A local image file is not automatically proof that the image was originally created by the authors.

Some visual assets may originate from external sources or may have been adapted from external material.

Where third-party material is used, its original copyright, attribution, and licensing conditions remain applicable.

The repository license does not automatically relicense third-party works.

---

# License

The original course textbook content covered by the repository's authorship is intended to be released under:

**Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)**

The applicable legal text is provided in [`LICENSE`](./LICENSE).

Official license page:

<https://creativecommons.org/licenses/by-nc-nd/4.0/>

## Practical Summary

For material covered by this license:

- You may read the material.
- You may download the material.
- You may share the original material in permitted non-commercial contexts.
- Appropriate attribution must be retained.
- Commercial use is not permitted under this license.
- Distribution of adapted material is not permitted under this license.

This section is only a practical summary. The legal terms in [`LICENSE`](./LICENSE) are authoritative.

---

# Copyright and Third-Party Material

## Copyright

Copyright in the original material belongs to the authors identified in this repository, subject to any rights belonging to third-party material.

Suggested copyright notice:

```text
Copyright © 2026

[Hamid Namjoo](https://hamidnamjoo.com/)
[Amir Hossein Hemmati](https://github.com/AmirHosseinHemati)
[AmirMohammad Asadjoo](https://github.com/Amir-Mohammd-Asadjoo)
Ali Nikvan
Reza Liaqat
Alireza Moghaddas
Golnoush Hosseinpour
Elham Izadi
```

## Attribution

When the original licensed material is redistributed, appropriate author attribution must be retained according to the license.

## Derivative Works

The `ND` condition reflects the authors' choice not to grant a general public license to distribute modified or adapted versions of the original course textbook.

For permissions outside the published license, contact the rights holders.

---

# Citation

If this repository is used as a source in:

- A university project
- A course presentation
- A report
- A paper
- A research project
- Educational material
- A tutorial
- A lecture

please cite the authors and link to the original repository.

## Suggested Citation

> Hamid Namjoo; Amirhossein Hemmati; Amir-Mohammad Asadjoo; Ali Nikvan; Reza Liaqat; Alireza Moghaddas; Golnoush Hosseinpour; Elham Izadi. *Data Mining Textbook, Version 2*. Islamic Azad University, Shiraz Branch, Faculty of Computer Engineering, Fall 2026, Academic Year 2026–2027. GitHub: https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes

## BibTeX

```bibtex
@misc{data_mining_textbook_v2_2026,
  title        = {Data Mining Textbook, Version 2},
  author       = {Namjoo, Hamid and
                  Hemmati, Amirhossein and
                  Asadjoo, Amir-Mohammad and
                  Nikvan, Ali and
                  Liaqat, Reza and
                  Moghaddas, Alireza and
                  Hosseinpour, Golnoush and
                  Izadi, Elham},
  year         = {2026},
  note         = {Islamic Azad University, Shiraz Branch,
                  Faculty of Computer Engineering,
                  Fall 2026,
                  Academic Year 2026--2027},
  url          = {https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes}
}
```

This BibTeX entry is a practical repository citation template and does not imply the existence of a DOI or separate formal publication record.

---

# Repository and GitHub

Official repository:

<https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes>

## Clone

```bash
git clone https://github.com/Amir-Mohammd-Asadjoo/data-mining-notes.git
```

## Enter the repository

```bash
cd data-mining-notes
```

## Start Jupyter

```bash
jupyter lab
```

or:

```bash
jupyter notebook
```

---

# Recommended Git Hygiene

The repository is intended to contain the course material and relevant assets, not local development metadata.

Avoid committing:

```text
.git/
.ipynb_checkpoints/
__pycache__/
*.py[cod]
```

The current repository keeps Jupyter checkpoint directories out of source control through `.gitignore`.

---

# Release Philosophy

The public repository is intended to preserve and distribute the current Version 2 course material in a stable, readable, and transparent form.

The release policy is intentionally simple:

- Completed chapters are published.
- Chapters still under development remain private until they are ready.
- Notebook and PDF versions are published together.
- Author attribution is explicit.
- Third-party material remains subject to its own rights.
- Future versions may revise both content and repository organization.

---

# Future Releases

Future releases may include:

- Publication of Chapter 9
- Publication of Chapter 11
- Revisions to existing chapters
- Corrections and typo fixes
- Updated examples
- Additional visualizations
- Additional implementations
- Improved dependency documentation
- Reproducibility improvements
- More detailed citation metadata
- GitHub release tags and version identifiers

When Chapters 9 and 11 are completed, this README should be updated accordingly.

---

# Quality and Accuracy

The notebooks and PDFs are educational course materials.

Care is taken during preparation, but educational material may still contain:

- Typographical errors
- Formatting issues
- Mathematical mistakes
- Implementation issues
- Broken links
- Incomplete explanations

Readers are encouraged to report issues through GitHub Issues.

When reporting a technical problem, include:

- Chapter number
- File path
- Section
- Description of the problem
- Error message, if applicable
- Python version
- Relevant package versions

This information makes issues easier to reproduce and resolve.

---

# Contribution and Issue Reporting

This repository is primarily a published educational resource, not a general-purpose software project.

However, technical and editorial feedback is welcome.

## Appropriate Issue Types

Examples include:

- Typographical errors
- Broken internal links
- Missing images
- Incorrect image paths
- Notebook rendering problems
- Code execution problems
- Formatting inconsistencies
- Incorrect chapter references
- Citation issues
- Attribution issues
- Documentation problems

## Suggested Issue Template

```text
Chapter:
File:
Section:
Problem:
Expected:
Observed:
Suggested correction:
Environment:
```

The maintainers may use GitHub Issues to track corrections and future revisions.

---

# Frequently Asked Questions

## What semester is this release for?

This release is prepared for **Fall 2026**, within the **2026–2027 academic year**.

## Is this the first version of the textbook?

No.

This repository contains **Version 2**.

It is the second edition of an earlier course textbook project, but Version 2 has been substantially redesigned and reworked rather than being a minor update.

## Is Version 2 just an edited copy of Version 1?

No.

The current version represents a major restructuring and reworking of the earlier material, including content organization, explanations, presentation, mathematical treatment, visual elements, and implementation-oriented material.

## Which chapters are currently public?

Chapters **1–8, 10, and 12** are currently published.

## Why are Chapters 9 and 11 missing?

They are still under development and have intentionally not been published yet.

## Will Chapters 9 and 11 be added later?

Yes. They are planned for future releases after completion.

## Do I need Python to read the textbook?

No.

The PDF files can be read without Python.

Python and Jupyter are required only when you want to execute Notebook cells.

## Can the notebooks be viewed on GitHub?

Yes.

GitHub can render the `.ipynb` files for reading.

## Can I execute the notebooks directly on GitHub?

GitHub's normal Notebook rendering is primarily for viewing. Local execution or a compatible notebook service is required for running the cells.

## Is this repository a software package?

No.

Its primary purpose is to distribute educational course textbook in Notebook and PDF formats.

## Does the repository license cover every file automatically?

No.

The repository license applies to material for which the authors have the rights necessary to grant that license. Third-party material remains subject to its own terms.

---

# Contact and Permissions

For uses clearly allowed by the published license, follow the conditions of that license.

For uses outside the published license, contact the rights holders before proceeding.

When requesting additional permission, it is useful to provide:

- The material you want to use
- The intended purpose
- Whether the use is educational or commercial
- Whether the material will be modified
- Where it will be distributed
- The expected audience

Additional permission is separate from the rights already granted by the published license.

---

# Acknowledgment

This collection is the result of collaborative work by the course design team under the supervision of the course instructor.

## Instructor

[**Dr. Amin Eskandari**](https://ir.linkedin.com/in/amin-eskandari-1756a73b)

## Design Team

- [**Hamid Namjoo**](https://hamidnamjoo.com/)

- [**Amir Hossein Hemmati**](https://github.com/AmirHosseinHemati)

- [**AmirMohammad Asadjoo**](https://github.com/Amir-Mohammd-Asadjoo)

- **Ali Nikvan**  

- **Reza Liaqat**  

- **Alireza Moghaddas**  

- **Golnoush Hosseinpour**  

- **Elham Izadi**

---

<p align="center">
  <strong>Data Mining Textbook — Version 2</strong><br>
  Islamic Azad University, Shiraz Branch<br>
  Faculty of Computer Engineering<br>
  Fall 2026 · Academic Year 2026–2027
</p>
