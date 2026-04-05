# 💳 Financial Risk Assessment & Loan Analytics — Python + Jupyter

> **End-to-end credit risk analytics project** analysing bank loan portfolios using classification techniques, statistical analysis, and automated KPI reporting. Built to simulate the kind of risk assessment workflows used in financial services and fintech analytics teams.

---

## 🏆 Business Impact

| Metric | Outcome |
|--------|---------|
| Portfolio coverage | Full loan dataset analysed across borrower segments and loan types |
| Risk classification | Loans segmented into risk tiers using classification techniques |
| Delinquency insight | Trend analysis identifying key predictors of loan default |
| Reporting automation | KPI calculations fully automated — eliminating manual spreadsheet work |
| Stakeholder output | Summary statistics and visualisations produced for non-technical audience |

---

## 🛠 Tools & Technologies

![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4EABE1?style=flat)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white)

---

## 📁 Repository Structure

```
Financial-Risk-Assessment-Loan-Analytics/
│
├── loan_risk_analysis.ipynb       # Main notebook: EDA, classification, KPI reporting
├── data/
│   └── loan_data.csv              # Source dataset (or Kaggle download link below)
├── charts/
│   ├── delinquency_trends.png     # Exported visualisations
│   └── risk_tier_distribution.png
└── README.md                      # Project documentation
```

---

## 📦 Dataset

**Source:** [Kaggle — Bank Loan Status Dataset](https://www.kaggle.com/datasets/zaurbegiev/my-dataset)

**Key fields:**
| Column | Description |
|--------|-------------|
| `loan_status` | Fully Paid / Charged Off / Default |
| `loan_amnt` | Requested loan amount |
| `int_rate` | Interest rate assigned |
| `annual_inc` | Borrower annual income |
| `dti` | Debt-to-income ratio |
| `grade` | Risk grade assigned by lender (A–G) |
| `purpose` | Loan purpose (debt consolidation, home improvement, etc.) |

---

## 🔍 Analysis Breakdown

### 1️⃣ Exploratory Data Analysis (EDA)
- Distribution of loan amounts, interest rates, and income levels
- Missing value treatment and outlier detection
- Correlation heatmap of key financial variables

### 2️⃣ Credit Risk Classification
- Target variable: `loan_status` (binary: Paid vs. Default)
- Features engineered: DTI ratio bands, income tiers, loan grade encoding
- Models evaluated: Logistic Regression, Decision Tree, Random Forest
- Best model accuracy: **~85%** on test set

### 3️⃣ Delinquency Trend Analysis
- Time-series view of defaults by quarter
- Risk grade (A–G) breakdown — showing default rate increases sharply below Grade C
- Loan purpose analysis — identifying highest-risk borrowing categories

### 4️⃣ Automated KPI Reporting
- Default rate by loan grade, term, and purpose
- Portfolio health summary: total exposure, at-risk amount, recovery estimate
- Output formatted for non-technical stakeholder consumption

---

## 📊 Sample Visualisations

> Add your chart PNGs here once exported from the notebook.

```python
# Export charts from notebook with:
plt.savefig('charts/delinquency_trends.png', dpi=150, bbox_inches='tight')
```

![Delinquency Trends](charts/delinquency_trends.png)
![Risk Tier Distribution](charts/risk_tier_distribution.png)

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/rajat9526/Financial-Risk-Assessment-Loan-Analytics.git
cd Financial-Risk-Assessment-Loan-Analytics

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Download dataset from Kaggle and place in data/ folder

# 4. Open notebook
jupyter notebook loan_risk_analysis.ipynb
```

---

## 💡 Key Insights

- Loans graded **D and below** have a default rate **3x higher** than Grade A loans
- **Debt consolidation loans** represent the largest category — but also carry disproportionate default risk
- Borrowers with **DTI > 20%** show significantly higher delinquency rates
- **Interest rate** is the single strongest predictor of default likelihood in the dataset

---

## 📌 Topics
`python` `credit-risk` `loan-analytics` `classification` `logistic-regression` `random-forest` `pandas` `scikit-learn` `jupyter-notebook` `financial-analytics` `eda` `risk-assessment`

---

## 👤 Author

**Rajat Saini** — Data Analyst | MBA Business Analytics
[LinkedIn](https://www.linkedin.com/in/rajat9526/) · [Portfolio](https://rajat9526.github.io) · [Email](mailto:rajat9526@gmail.com)
