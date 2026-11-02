# 🏦 Credit Card Fraud Detection — Statistical Analysis

## 🎯 Project Overview

This project investigates credit card transactions using descriptive and inferential statistical techniques in Python.

The main objective is to explore the characteristics of fraudulent and legitimate transactions and evaluate the application of probability distributions to real-world financial data.

📈  The statistical analysis focuses on three probability distributions:

- **Binomial Distribution:** Investigating the probability of fraudulent transactions.
- **Poisson Distribution:** Analysing transaction counts over fixed time intervals.
- **Normal Distribution:** Investigating the distribution and statistical characteristics of selected numerical variables.

The project also examines the impact of class imbalance, skewness, and the assumptions associated with each statistical distribution.

## Dataset

**Source:** [Credit Card Fraud Detection — Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset contains credit card transactions made by European cardholders during September 2013, covering a period of two days.

| Dataset characteristic | Description |
|---|---|
| Total transactions | 284,807 |
| Fraudulent transactions | 492 |
| Legitimate transactions | 284,315 |
| Total features | 31 |
| Fraud proportion | Approximately 0.172% |

### 👨🏾‍🔬 Dataset Features

- `Time`: Seconds elapsed between each transaction and the first transaction.
- `V1`–`V28`: Anonymised numerical features obtained through Principal Component Analysis (PCA).
- `Amount`: Transaction amount.
- `Class`: Target variable identifying fraudulent (1) and legitimate (0) transactions.

The dataset presents a highly imbalanced class distribution, which is an important consideration throughout the statistical analysis.

## 🎯 Project Objectives

1. Explore the dataset using descriptive statistics.
2. Investigate the distribution of legitimate and fraudulent transactions.
3. Analyse numerical variables and their statistical characteristics.
4. Apply the Binomial distribution to model fraudulent transaction occurrences.
5. Apply the Poisson distribution to investigate transaction counts over time.
6. Investigate the suitability of the Normal distribution for selected numerical variables.
7. Compare and critically evaluate the statistical distributions used.

## 👨🏾‍🏫 Methodology

The project follows the stages below:

1. **Data Loading and Inspection:** Importing the dataset and examining its structure.
2. **Data Quality Assessment:** Investigating missing values, duplicates, and data consistency.
3. **Exploratory Data Analysis:** Calculating descriptive statistics and creating visualizations.
4. **Binomial Distribution:** Modelling binary fraudulent transaction outcomes.
5. **Poisson Distribution:** Modelling transaction counts over defined time intervals.
6. **Normal Distribution:** Investigating continuous numerical variables.
7. **Statistical Comparison:** Evaluating the suitability, assumptions, and limitations of the distributions.
8. **Conclusion:** Summarising the findings and statistical insights.

## 🗂 Technologies and Libraries

The project uses Python and the following libraries:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## 📂 Repository Structure

```text
CCT_STDA_CA_01_40S/
│
├── data/
│   └── creditcard.csv
├── docs/
│   ├── CCT_STDA_CA_01_40S_2026438.docx
│   ├── Harvard_Referencing_Handbook__includes_AI_new.pdf
│   └── Stats- HDip DBA Sept-26 CA-1 40%.docx
├── notebooks/
│   └── CCT_STDA_CA_01_40S_2026438.ipynb
├── .gitignore
├── .python-version
├── LICENSE
├── README.md
├── requirements-dev.txt
└── requirements.txt
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/CCT-Dublin/CCT_STDA_CA_01_40S.git

cd CCT_STDA_CA_01_40S
```

### 2. Create a Virtual Environment

```bash
conda create -n $(basename $(pwd)) python=3.14.*
```

Activate the environment:

**macOS / Linux**

```bash
conda activate $(basename $(pwd))
```


### 3. Install Dependencies

```bash
pip install -r requirements-dev.txt
```

### 4. Download the Dataset ~~ ⚠⚠ This part is optional! ⚠⚠

Download the dataset directly from Kaggle:

[Credit Card Fraud Detection — Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Extract `creditcard.csv` and place it inside the `data/` directory.

```text
data/
└── creditcard.csv
```


* **License** [Database: Open Database, Contents: Database Contents](https://opendatacommons.org/licenses/dbcl/1-0/)
* **Note:** The original dataset is `not included` in this repository because of its file size. Users must download it independently from Kaggle.

### 5. Run the Jupyter Notebook

```bash
jupyter lab
```

Open:

`notebooks/CCT_STDA_CA_01_40S_2026438.ipynb`


## 📔 Academic Context

This project was developed as part of the **Higher Diploma in Data Analytics in Business**, under the *Stats for Data Analytics* module at CCT College Dublin.

**Assessment:** CA1 — Individual Assignment
**Weighting:** 40%

---

*This repository is intended for academic and educational purposes.*

## Document Version

| Versão Do Document |        Editor      |    Data    |  Percentage Complete  |
|        :---:       |        :---:       |    :---:   |         :---:         |
|        1.0.0       | Matheus S. Silva   | 2026-10-31 |          86%          |