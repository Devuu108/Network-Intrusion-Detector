## Network-Intrusion-Detector
Network Intrusion Detection Project with code and Documents

In this project study we need to predict anomalies and attacks in the network.

# Problem :

The task is to build network intrusion detection system to detect anomalies and attacks in the network.

We will use Machine Learning ALgorihtms in this project.

We have used Python Programming for project

# Research Paper (Base paper):

1. https://esource.dbs.ie/handle/10788/4251
2. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3428211
3. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8049129/
4. https://journalofbigdata.springeropen.com/articles/10.1186/s40537-018-0145-4

## How to Reach me :

### Mail : devanshinaar5680@gmail.com

## Network Intrusion Detector
# Project Overview

This project implements a machine learning-based approach to detect and classify network intrusions. By analyzing network traffic patterns, the system distinguishes between normal connections and potential attacks (anomalies). The implementation utilizes Python’s data science stack to preprocess large-scale network logs and prepare them for classification models.

# Dataset
The system is trained and evaluated using a comprehensive network intrusion dataset containing approximately 22,544 records with 40 distinct features. Key attributes include:

Connection Features: Duration, protocol type (TCP/UDP/ICMP), and service type.

Traffic Statistics: Source/destination bytes, error rates (serror, rerror), and host-based counts.

Target Class: A binary classification indicating whether the traffic is normal or an anomaly.

# Key Technical Workflow

Data Exploration: High-level statistical analysis and uniqueness checks to understand feature distributions and identify constant or low-variance variables.

Preprocessing: * Handling categorical data (e.g., protocol types and flags).

Feature scaling using MinMaxScaler to normalize traffic metrics.

Dimensionality reduction through VarianceThreshold to remove non-informative features.

Modeling: Implementation of a Decision Tree Classifier to provide interpretable rules for detecting intrusion signatures.

Performance Metrics: Evaluation based on accuracy and the system's ability to minimize false negatives in a security context.

# Tech Stack

Language: Python
Libraries: Pandas, NumPy, Scikit-learn
Environment: Jupyter Notebook / Google Colab
