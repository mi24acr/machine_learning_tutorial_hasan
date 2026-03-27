# Gaussian Mixture Models: Soft Clustering with Expectation–Maximisation

This repository contains my machine learning tutorial on **Gaussian Mixture Models (GMMs)**. The tutorial focuses on how GMMs perform **soft clustering** and how the **Expectation–Maximisation (EM)** algorithm is used to fit the model.

The project was created for an MSc Data Science assignment and includes:
- a PDF tutorial
- a Jupyter notebook with the full code
- the dataset used in the worked example
- generated figures
- a requirements file
- a licence file

## Tutorial focus

The main aim of this tutorial is to explain the core intuition behind Gaussian Mixture Models and why they are useful when uncertainty matters. Unlike hard clustering methods, a GMM does not force each observation into one fixed cluster. Instead, it estimates the probability that each observation belongs to each component.

The tutorial uses the **Palmer Penguins** dataset and focuses on:
- Gaussian components
- soft cluster membership
- covariance structure
- ambiguous observations
- model confidence
- model selection using BIC

## Repository contents

```text
.
├── GMM_Tutorial_Gaussian_Mixture_Models_revised_v2.pdf
├── GMM_Tutorial_Gaussian_Mixture_Models_revised_v2.docx
├── gmm_tutorial_notebook_v2.ipynb
├── penguins.csv
├── requirements_gmm_tutorial.txt
├── LICENSE
└── gmm_figures/
