# BAYESIAN INFERENCE FOR MODELING AND PREDICTING STUDENT EXAM PERFORMANCE

![Academic Project](https://img.shields.io/badge/Project_Type-Academic%20%7C%20Data%20Science-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Language](https://img.shields.io/badge/Language-R-blue)
![Modeling](https://img.shields.io/badge/Modeling-Bayesian%20Inference-brightgreen)

## Overview

This academic data science project focuses on predicting and analyzing student performance in mathematics exams. It leverages a dataset of 1,000 students' records to explore how **demographic and behavioral factors** (like lunch type and test preparation) influence their math scores.

The study compares a traditional Frequentist (OLS) model with a **Bayesian Linear Regression** approach, demonstrating the superior **uncertainty quantification** provided by the Bayesian framework through credible intervals.

### Key Findings

* **Lunch Type is Critical:** Students receiving a **Standard Lunch** scored approximately **11 points higher** than those with free/reduced lunch, highlighting the role of socioeconomic status.
* **Test Preparation Pays Off:** Students who **completed a test preparation course** scored about **5.5 points higher**.
* **Modeling Advantage:** The Bayesian framework allowed for a robust, probabilistic understanding of each predictor's impact.

---

## Project Contents

| File Name | Description |
| :--- | :--- |
| `bayesianfinal.ipynb` | The primary **R/Jupyter Notebook** containing all data cleaning, the **Frequentist** (`lm()`) model, and the **Bayesian** (`brm()`) model implementation. |
| `StudentsPerformance.csv` | The **raw dataset** (1000 student records) used for the analysis. |
| `bayesian report updated.docx` | The comprehensive **academic report** detailing the methodology, model comparison, diagnostic checks, and full discussion of the results. |

---

## Setup and Execution

### Prerequisites

This project was built and executed in the **R programming environment** using a Jupyter Notebook with an R kernel.

You will need:
* **R** (latest version recommended)
* **RStudio** or a **Jupyter environment** with an R kernel.

### Dependencies

Install the required R packages:

```R
install.packages(c("brms", "rstan", "Rcpp", "ggplot2", "GGally"))


Running the Analysis
Clone the Repository (or download the files).

Open the file bayesianfinal.ipynb in your Jupyter environment.

The notebook begins by loading the StudentsPerformance.csv file, which is included in this repository.

Execute the cells sequentially to perform data preprocessing, fit the Frequentist model, and run the Bayesian MCMC analysis (which utilizes the NUTS sampler).


Modeling Approach
The final model selected was the Bayesian Linear Regression model with the following structure:

$$\text{Math.score} \sim \text{gender} + \text{race.ethnicity} + \text{parental.education} + \text{lunch} + \text{test.preparation.course} $$ * **Model:** Bayesian Linear Regression, fitted with the `brms` package. * **Sampling:** Markov Chain Monte Carlo (MCMC) using the **No-U-Turn Sampler (NUTS)**. * **Priors:** Weakly informative Normal (0, 10) priors were used for the regression coefficients. ## 📧 Contact **Vigneshwar Lokoji** * *Feel free to connect or ask questions about the project or code.* ``` ```$$
