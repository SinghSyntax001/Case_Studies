
# Inferential Statistics Case Study

This repository contains an analysis of inferential statistics using two datasets, `bookseller.csv` and `debugging.csv`, provided in this case study.

## Overview

The objective of this analysis is to understand the data from two different perspectives:

1. **Bookseller Data**: Analyzing the daily number of books sold over a period of time.
2. **Debugging Data**: Evaluating the time taken to fix bugs in a software system.

The analysis uses inferential statistical methods, including descriptive statistics and hypothesis testing, to gain insights into each dataset.

## Datasets

- **bookseller.csv**: Contains daily sales data of books, with columns `S.No`, `Date`, and `Number of Books Sold`.
- **debugging.csv**: Includes bug fixing times, with columns `Bug ID` and `Time Taken to fix the bug`.

## Analysis

For each dataset, the analysis includes the following steps:

1. **Descriptive Statistics**: Provides basic statistical measures, such as mean, median, standard deviation, etc.
2. **Inferential Analysis**: A one-sample t-test is conducted on both datasets:
   - **Bookseller Data**: Tests whether the average number of books sold per day is significantly different from a hypothetical mean (e.g., 95 books).
   - **Debugging Data**: Tests if the mean time to fix bugs significantly differs from a hypothetical time (e.g., 2.5 hours).

## Results

The notebook provides both descriptive and inferential results, helping in understanding sales patterns and debugging times.

## Files

- `Assignment -1 (bookseller_debugging).ipynb`: Jupyter Notebook with data analysis and statistical testing.
- `bookseller.csv`: CSV file with bookseller data.
- `debugging.csv`: CSV file with debugging data.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`




