# Credit Card Launch: EDA and A/B Testing

Welcome to the **Credit Card Launch: EDA and A/B Testing** project. In this project, we analyze bank customer data to identify optimal customer segments for launching a new credit card. We then conduct A/B testing to evaluate if the new card performs better than the existing one.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [A/B Testing](#a-b-testing)
- [Results](#results)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to support a data-driven launch strategy for a new credit card by:
1. Performing **Exploratory Data Analysis (EDA)** on bank customer data to identify promising customer groups for the new product.
2. Conducting **A/B testing** to determine if the new card yields higher engagement and better performance compared to the current credit card offering.

## Dataset

The data used in this project comes from internal banking sources, containing customer demographics, behavioral indicators, and engagement metrics with existing credit card products. **(If the dataset is public, consider adding the link here)**.

## Project Structure

This repository contains the following main files and folders:

- **`data/`** - Contains all dataset files.
- **`notebooks/`** - Jupyter notebooks for EDA and A/B testing analyses.
- **`src/`** - Python scripts for data processing, analysis, and visualization.
- **`results/`** - Summary files of results and findings.
- **`README.md`** - Project overview and guide.

## Exploratory Data Analysis (EDA)

The EDA process includes:

- **Data Cleaning and Preparation:** Removing duplicates, handling missing values, and feature engineering.
- **Descriptive Statistics:** Understanding data distribution, central tendency, and dispersion metrics for key variables.
- **Visual Analysis:** Graphs and plots to explore customer demographics and behaviors, with a focus on identifying patterns and trends.
- **Segmentation Analysis:** Identifying potential customer segments based on demographic and behavioral characteristics, helping to target the right group for the new credit card.

## A/B Testing

### Objective

To evaluate if the new credit card leads to improved outcomes compared to the old credit card, we perform A/B testing by dividing customers into control (old card) and test (new card) groups.

### Hypothesis

- **Null Hypothesis (H₀):** There is no significant difference in performance metrics (e.g., engagement rate) between the new and old credit cards.
- **Alternative Hypothesis (H₁):** The new credit card performs significantly better than the old credit card.

### Metrics Analyzed

The primary and secondary metrics assessed include **customer engagement, average spending, retention rates**, and **activation rates**.

### Testing Method

We used statistical tests (e.g., t-tests, chi-squared tests) to analyze differences between the control and test groups. The level of significance is set at **0.05**.

## Results

The analysis indicates that **[summary of findings – for example: "the new credit card significantly increases customer engagement in the targeted demographic group, outperforming the existing card."]**

> Detailed results and visualizations can be found in the `results/` folder and in the A/B testing notebook.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Vraj-Data-Scientist/credit-card-launch-EDA-ABtesting.git
