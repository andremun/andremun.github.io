---
title: "MATILDA – Melbourne Algorithm Test Instance Library with Data Analytics"
excerpt: "Cloud-based platform for Instance Space Analysis, supporting rigorous algorithm benchmarking across multiple domains."
collection: portfolio
permalink: /portfolio/matilda
date: 2019-01-01
---

[MATILDA](https://matilda.unimelb.edu.au/matilda/) (**Melbourne Algorithm Test Instance Library with Data Analytics**) is a Software-as-a-Service cloud platform implementing the **Instance Space Analysis (ISA)** methodology. ISA provides a visual, data-driven framework for understanding algorithm strengths and weaknesses across a space of problem instances, enabling principled algorithm selection and benchmark construction. I am the lead developer of MATILDA and have been leading its reengineering since 2023, with a new version expected to launch in mid-2026.

## What MATILDA does

MATILDA enables researchers to:
- **Download** benchmark datasets for library problems, including existing algorithm performance results, instance features, and instance space visualisations
- **Upload** a new algorithm's performance metrics and visualise its comparative strengths and weaknesses across the constructed instance space
- **Create** instance spaces for new problems to examine the diversity and adequacy of existing benchmarks
- **Generate** objective metrics and visualisations of algorithm performance and problem instance distributions
- **Receive recommendations** on which algorithm is predicted to perform best in certain regions of the instance space

## Problem domains available in MATILDA

Combinatorial optimisation (TSP, Graph Colouring, Knapsack, Bin Packing, Job Shop Scheduling, Timetabling, Maximum Flow, Quadratic Assignment), Continuous black-box optimisation (single- and multi-objective), Machine learning (Regression, Classification, Anomaly Detection, Clustering, Time Series Forecasting), and Search-based Software Engineering.

## Key facts

- **200+ registered users** from teams in Australia, Austria, China, the UK, and elsewhere
- **3,000+ jobs processed** since launch in 2019
- Part of the **OPTIMA toolkit** — a set of industry-ready computational tools for advanced optimisation
- The computational engine is also available as a [MATLAB toolkit](https://github.com/andremun/InstanceSpace) and a [Python package](https://pypi.org/project/instancespace/)

## Core methodology papers

The ISA methodology underpinning MATILDA is summarised in:

- K. Smith-Miles and **M.A. Muñoz** (2023) [*Instance Space Analysis for Algorithm Testing: Methodology and Software Tools*](https://doi.org/10.1145/3572895). *ACM Computing Surveys*, 55(12:255)1–31 **(IF 2023: 23.8)**

Earlier foundational contributions from Muñoz include:

- **M.A. Muñoz** and K.A. Smith-Miles (2017) [*Performance analysis of continuous black-box optimization algorithms via footprints in instance space*](https://doi.org/10.1162/EVCO_a_00194). *Evolutionary Computation*, 25(4)529–554 **(IF 2024: 3.4)**

- **M.A. Muñoz**, L. Villanova, D. Baatar and K. Smith-Miles (2018) [*Instance spaces for machine learning classification*](https://doi.org/10.1007/s10994-017-5629-5). *Machine Learning*, 107(1)109–147 **(IF 2024: 4.3)**

- **M.A. Muñoz** and K. Smith-Miles (2020) [*Generating new space-filling test instances for continuous black-box optimization*](https://doi.org/10.1162/evco_a_00250). *Evolutionary Computation*, 28(3)379–404 **(IF 2024: 3.4)**

- S. Kandanaarachchi, **M.A. Muñoz**, R.J. Hyndman and K. Smith-Miles (2020) [*On normalization and algorithm selection for unsupervised outlier detection*](https://doi.org/10.1007/s10618-019-00661-z). *Data Mining and Knowledge Discovery*, 34:309–354 **(IF 2024: 4.3)**

## Software papers

- Y.B. Güzel, K. Khare, N. Harvey, K. Dsouza, D.H. Jang, J. Chen, C.Z. Lam and **M.A. Muñoz** (2025) [*instancespace: a Python Package for Insightful Algorithm Testing through Instance Space Analysis*](https://doi.org/10.1016/j.softx.2025.102246). *SoftwareX*, 31:102246 **(IF 2024: 2.4)**

- B. Oldfield, S. Kandanaarachchi, Z. Xu and **M.A. Muñoz** (2025) [*An Item Response Theory-based R module for Algorithm Portfolio Analysis*](https://doi.org/10.1016/j.softx.2025.102239). *SoftwareX*, 31:102239 **(IF 2024: 2.4)**
