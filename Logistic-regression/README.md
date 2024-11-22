# Logistic Regression for Car Insurance Prediction

This project leverages a **Logistic Regression** model to predict whether a customer will purchase car insurance based on demographic, behavioral, and interaction data collected during marketing campaigns. The project includes steps for data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

## Dataset

Two datasets were provided for this project:
1. **Training Dataset**: Contains 4,000 entries with 19 features and the target variable `CarInsurance` (0 = No, 1 = Yes).
2. **Testing Dataset**: Contains 1,000 entries with 18 features. The task is to predict the `CarInsurance` outcome.

### Key Features:
- **Demographics**: `Age`, `Job`, `Marital`, `Education`
- **Behavioral**: `Balance`, `DaysPassed`, `NoOfContacts`, `PrevAttempts`
- **Campaign Interaction**: `Communication`, `LastContactMonth`, `Outcome`

---

## Project Workflow

### 1. Data Preprocessing
- Handled missing values using mode (for categorical) and median (for numerical) imputations.
- Derived a new feature `CallDuration` by calculating the difference between `CallStart` and `CallEnd` (if applicable).
- Encoded categorical variables using One-Hot Encoding.
- Scaled numerical features using Standard Scaling.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of key features.
- Examined relationships between features and the target variable (`CarInsurance`).
- Highlighted important patterns in customer demographics and behaviors.

### 3. Model Training
- Split the training data into training (80%) and validation (20%) sets.
- Used **Logistic Regression** for binary classification.
- Evaluated model performance using metrics:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC and Precision-Recall Curves.

### 4. Prediction
- Applied the trained model to the test dataset.
- Generated probabilities and predicted labels for the `CarInsurance` column.

---

## Results

- **Model Accuracy**: Achieved ~80% on the validation dataset.
- **Key Metrics**:
  - Precision: 79% for `CarInsurance = 1`
  - Recall: 70% for `CarInsurance = 1`
  - ROC-AUC: 0.85 (Good model fit)

### Confusion Matrix:
|           | Predicted: No | Predicted: Yes |
|-----------|---------------|----------------|
| **Actual: No** | 419           | 60             |
| **Actual: Yes** | 95            | 226            |

### Prerequisites:
- Python 3.7 or higher
- Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`
