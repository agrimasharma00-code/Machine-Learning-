# Machine Learning Projects

A collection of machine learning projects covering exploratory data analysis (EDA), data preprocessing, feature engineering, and predictive modelling.

---

## Projects

### 1. Insurance Charges Prediction

**Notebooks:** `Insurance project ML1.ipynb` · `Insurance ML_Prediction.ipynb`

**Dataset:** [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) (Kaggle)

**Goal:** Predict individual medical insurance charges based on personal attributes.

**Steps covered:**
- **EDA** – distribution plots, count plots, box plots, and correlation heatmap
- **Data Cleaning** – duplicate removal, null-value check
- **Preprocessing** – label encoding (`sex`, `smoker`), one-hot encoding (`region`)
- **Feature Engineering** – BMI categorisation (underweight / normal / overweight / obese), Pearson correlation and chi-squared tests for feature selection, StandardScaler for numeric columns
- **Modelling** – Linear Regression (`sklearn`)
- **Evaluation** – R² score and Adjusted R² score

**Key features selected:** `age`, `bmi`, `children`, `is_female`, `is_smoker`, `region_southeast`, `bmi_category_obese`

---

### 2. Heart Disease Analysis

**Notebook:** `heart.ipynb`

**Dataset:** [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) (Kaggle)

**Goal:** Analyse patient data and prepare features for heart disease classification.

**Steps covered:**
- **EDA** – distribution plots, count plots by target variable, box plots, violin plots, correlation heatmap
- **Data Cleaning** – handling zero-value outliers in `Cholesterol` and `RestingBP` by replacing them with column means
- **Preprocessing** – one-hot encoding of categorical variables (`Sex`, `ChestPainType`, `RestingECG`, `ST_Slope`), StandardScaler for numeric columns (`Age`, `Cholesterol`, `MaxHR`, `RestingBP`, `Oldpeak`)

---

## Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation |
| `numpy` | Numerical computation |
| `matplotlib` / `seaborn` | Visualisation |
| `scikit-learn` | Preprocessing, modelling, evaluation |
| `scipy` | Statistical tests (Pearson correlation, chi-squared) |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/agrimasharma00-code/Machine-Learning-.git
cd Machine-Learning-

# Install dependencies
pip install numpy pandas seaborn matplotlib scikit-learn scipy

# Open any notebook
jupyter notebook
```

