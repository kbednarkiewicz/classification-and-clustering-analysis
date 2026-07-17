# Advanced Classification & Clustering Analysis

## Overview

This project presents a comparison of advanced machine learning methods for classification and clustering tasks.
The analysis focuses on ensemble learning, Support Vector Machines, and unsupervised clustering methods.
The main goal was to compare algorithms, tune selected parameters, evaluate performance, and interpret results.
The project was completed as part of a university course. The final report was prepared in Polish using R Markdown.


## Authors

- Katarzyna Bednarkiewicz
- Ewelina Dąbrowa

## Dataset

The project uses the **Glass Identification Dataset** from the `mlbench` R package.

The dataset contains chemical measurements of glass samples collected for forensic analysis. The tasks were to classify glass types and analyze their natural groupings using clustering methods.

## Methods

### Classification

Implemented and compared:

- Decision Tree
- Bagging
- Boosting
- Random Forest
- Support Vector Machines (linear, polynomial, and radial kernels)

The analysis included:

- comparison of ensemble learning methods,
- SVM kernel selection,
- hyperparameter tuning (`C`, `gamma`),
- evaluation of classification accuracy.

### Clustering

Implemented:

- K-means,
- PAM (Partitioning Around Medoids),
- AGNES hierarchical clustering.

Cluster quality was evaluated using:

- Silhouette coefficient,
- external validation against original classes.

## Technologies

- R
- R Markdown
