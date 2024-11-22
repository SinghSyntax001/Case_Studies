# Linear Regression Assumption Analysis and Future Earnings Prediction

This project analyzes the assumptions of linear regression and predicts future labor earnings (1978) using historical data (1974 and 1975). The project is built with Python and employs statistical and machine learning techniques.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

---

## Overview
This project predicts the labor earnings for 1978 using historical data provided for 1974 and 1975. It checks for and validates the key assumptions of linear regression before building the prediction model.

### Linear Regression Assumptions Validated:
1. Linearity
2. Homoscedasticity
3. Multicollinearity
4. Independence of Errors
5. Normal Distribution of Errors

---

## Dataset
The dataset contains:
- **Age**: Age of the individual.
- **Race**: Binary indicator of whether the individual is Black.
- **Education**: Categorical levels of education.
- **Hispanic**: Binary indicator of Hispanic ethnicity.
- **Marital Status**: Binary indicator of marriage status.
- **Earnings**: Labor earnings for 1974, 1975, and 1978.

The data file `LRA.csv` is preprocessed for missing values, categorical encoding, and feature scaling.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/linear-regression-assumptions.git
   cd linear-regression-assumptions
