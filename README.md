# Negation and Uncertainty Detection Project - Group 1

## Members
- Marino Oliveros Blanco  NIU: 1668563
- Pere Mayol Carbonell  NIU: 1669503
- Andreu Gascón Marzo  NIU: 1670919
- Judith Zaragoza López NIU: 1634071
  
## Introduction

This project aims to implement three different sequence tagging techniques to solve the task of Detection of Negation and Uncertainty in medical reports written in Catalan and Spanish. The three methods to be implemented include:

1. Rule-based algorithm using basic text processing tools.
2. Machine learning system.
3. Deep learning system, employing at least a simple LSTM architecture.

## Data

The dataset consists of real medical notes manually labeled to identify negation and uncertainty cues along with the affected scopes. Each sample in the dataset contains text and corresponding annotations indicating negation/uncertainty scopes. This is provided in a .json format.

## Tasks

The project tasks include:

- Literature Review: Surveying existing literature on negation and speculation detection in NLP.
- Method Design: Designing methods based on literature review and potential modifications.
- Data Pre-processing: Preparing the dataset for analysis and model training.
- Rule-Based Method: Implementing a handcrafted rule-based system for negation/uncertainty detection.
- Machine Learning Method: Developing a machine learning-based approach utilizing text features for detection.
- Deep Learning Method: Implementing a deep learning approach, initially utilizing LSTM, for negation/uncertainty detection.

## Methodology

The scientific method will be applied throughout the project:

1. Hypothesis Design: Formulate hypotheses based on the designed methods and potential improvements.
2. Experiment Design: Develop experiments to test hypotheses under various conditions.
3. Results Analysis: Analyze experiment results, reevaluate hypotheses, and iterate as necessary.

## Rule-based algorithm
- UMLS tagging


## ML approach
- CRF


## DL approach
- BiLSTM with Class Weights
