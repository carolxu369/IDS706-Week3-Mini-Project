# Week 3: Polars Descriptive Statistics Script

This is a Python GitHub Template Repository that creates Polars Descriptive Statistics Script:
- A .devcontainer configuration for a Python environment
- A Makefile with commands for setup, testing, and linting
- GitHub Actions for CI/CD
- A requirements.txt for project dependencies
- A README.md with setup and usage instructions
- Python script using Polars for descriptive statistics
- Read a dataset (CSV or Excel)
- Generate summary statistics (mean, median, standard deviation)
- Create at least one data visualization

## Prerequisites

- Python 3.9 or higher installed
- polars
- matplotlib
- pytest
- pylint
- seaborn

## Report

For this polars descriptive statistics script, I used the polars, matplotlib, and seaborn libraries in python to read a “grade.xlsx” and calculated the mean, median, and standard deviation.
Then, I generated three plots as following.

- Mean: 72.10714285714286
- Median: 75.5
- Standard Deviation: 19.87938492647459

![Distribution Plot](data/distribution%20plot.png)
![Box Plot](data/box%20plot.png)
![KDE Plot](data/KDE%20plot.png)
