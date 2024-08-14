## A scientific article about Bayesian Networks using continuos variables to calculate the probability of a person having chronic kidney disease (CKD).

# General information
This project focuses on the application of Gaussian Bayesian Networks (GBNs) to model Chronic Kidney Disease (CKD), exploring both linear and nonparametric modeling approaches. The primary goal is to identify key risk factors and accurately predict disease progression by comparing these models, ultimately determining which approach best fits the data. By achieving this, the project aims to provide healthcare professionals with a powerful tool to identify individuals at risk of developing CKD at an early stage, enabling timely interventions and potentially improving patient outcomes through more personalized and preventive care strategies.

# Project Structure 
**Data Collection** Data from interviews with health experts were used to build the networks.

**Modeling**

-Linear Gaussian Bayesian Network: Models linear relationships between continuous variables using Gaussian distributions.
![imagen](https://github.com/user-attachments/assets/eb194fc0-1962-4a4c-b920-d5f68b83d4b2)

-Nonparametric Bayesian Network: Captures more complex and nonlinear relationships between continuous variables.
![imagen](https://github.com/user-attachments/assets/f82ed927-bbcc-4836-ac89-89c7dff2b17c)

**Evaluation** The models were evaluated using BIC and AIC metrics, determining that nonparametric approaches performed better.
<p align="center">
  <img src="https://github.com/user-attachments/assets/5d3d07d7-bfc0-4e02-b271-cf53f7db8022" alt="imagen" width="400">
</p>

# Python
Used Python to clean the database for a sample of patients with and without CKD.

# R
Used R script to elaborate a DAG (Directed Acyclic Graph) which represents the dependence relationships of variables to determine whether a patient is prone to chronic kidney disease and to be able to detect it in time
