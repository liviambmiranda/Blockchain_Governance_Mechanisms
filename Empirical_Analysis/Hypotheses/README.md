# Overview

This repository contains Python code designed to evaluate statistical properties of survey data (from a questionnaire using a seven-point Likert-type scale with end points of ‘strongly disagree’ and ‘strongly agree’) using non-parametric methods. It includes functionality to calculate:

1. **Cliff’s Delta** (a effect size measure),  
2. **Confidence intervals for Cliff’s Delta**, and  
3. **One-tailed Wilcoxon signed-rank tests** to compare survey medians against a hypothesized value.

This is particularly useful for analyzing data collected via Likert-type scales or ordinal datasets.

## Table of Contents :memo:

1. [Requirements](#requirements)  
2. [Data Structure](#data-structure)  
3. [Key Features](#key-features)  
4. [How to Run](#how-to-run)  

---

## Requirements :wrench:

- **Python 3.7+**  
- **NumPy** (for numerical operations)  
- **SciPy** (for statistical tests and distributions)  

Install the required packages via:

```bash
pip install numpy scipy
