# Applied Atatistics Assesment
Applied Statistics Assesment

** by Ciaran Moran (G00426050@atu.ie)

# Applied Statistics Assignment

This repository contains my assesment submission for the module Applied Statistics, where various statistical tests are performed on the `PlantGrowth` dataset to analyze the differences between different treatment groups.
  
### Project Overview

In this project, we perform **statistical analysis** using Python to determine whether there are significant differences between different treatment groups of plants. Specifically, we perform:
1. A **t-test** to compare two treatment groups (`trt1` and `trt2`) and check if there is a significant difference in plant weights between them.
2. An **ANOVA (Analysis of Variance)** test to analyze whether there is a significant difference between three treatment groups (`ctrl`, `trt1`, and `trt2`).

The data used for this analysis is from the `PlantGrowth` dataset, which includes plant weights under different treatment groups.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Installation and Requirements](#installation-and-requirements)
- [Running the Notebook](#running-the-notebook)
- [Using the `requirements.txt`](#using-the-requirementstxt)
- [Statistical Analysis](#statistical-analysis)
  - [T-Test](#t-test)
  - [ANOVA](#anova)
- [Results Interpretation](#results-interpretation)
- [References](#references)
- [License](#license)

---

## Dataset Description

The dataset is taken from the R `datasets` library and is available from [R Datasets](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv). It contains the following columns:
- **weight**: The weight of the plants.
- **trt**: The treatment group the plant belongs to, with three possible values: `ctrl`, `trt1`, and `trt2`.

---

## Installation and Requirements

Before running the notebook, ensure that you have the following Python libraries installed:

- `pandas`
- `scipy`
- `numpy`
- `matplotlib` (optional, for visualizations)

You can install the required libraries by running the following commands:

```bash
pip install pandas scipy numpy matplotlib
