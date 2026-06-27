# 📡 TECO Telecom — Customer Churn Analysis & Retention Strategy

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=python&logoColor=white)

## 📌 Project Overview

This project analyzes **customer churn** for TECO, a telecommunications company, 
to identify key drivers of churn and provide actionable recommendations for 
customer retention.

The analysis reveals that **26.5% of the customer base has churned**, posing a 
significant revenue risk. Insights are derived from demographic, behavioral, 
and service-related factors across the entire customer base.

> 💡 **What is Customer Churn?** Churn means a customer stopped using the 
> service. In telecom, losing customers is very expensive — it costs 5-7x more 
> to acquire a new customer than to retain an existing one. Identifying 
> at-risk customers early is critical for business survival.

---

## 🎯 Business Questions Answered

| # | Question |
|---|---|
| 1 | What percentage of customers are churning? |
| 2 | Which customer demographics are at highest risk? |
| 3 | How does contract type affect churn? |
| 4 | Which services reduce churn the most? |
| 5 | What payment methods are linked to higher churn? |
| 6 | What retention strategies should be prioritized? |

---

## 🔑 Key Finding — Overall Churn Rate

> ⚠️ **26.5% of TECO customers have churned** — representing significant 
> revenue loss that could be reduced with targeted retention strategies.

---

## 📊 Key Findings by Category

### 👥 Demographics
| Factor | Finding |
|---|---|
| Senior Citizens | Churn at disproportionately higher rate |
| Gender | No meaningful impact on churn |

### ⏳ Tenure Impact
| Tenure | Churn Rate |
|---|---|
| 1–2 months | 45–50% |
| 6–12 months | 25–35% |
| 24+ months | Below 10% |

> 💡 **Early experience is critical** — nearly half of new customers leave 
> within the first 2 months.

### 📄 Contract Type
| Contract Type | Churn Rate |
|---|---|
| Month-to-month | ~55–60% of all churn cases |
| One-year | ~11–13% |
| Two-year | Less than 5% |

### 🛠️ Add-on Services
| Service Status | Churn Rate |
|---|---|
| Without add-ons | 35–45% |
| With add-ons | Less than 15% |

> 💡 Bundling services increases engagement and switching costs — dramatically 
> reducing churn.

### 🌐 Internet Service Type
| Service Type | Churn Rate |
|---|---|
| Fiber optic | ~40–42% |
| DSL | ~19–21% |
| No internet service | Less than 8% |

> ⚠️ Fiber optic users churn at twice the rate of DSL users — despite paying 
> more. This suggests a service quality or value perception issue.

### 💳 Payment Method
| Payment Method | Churn Rate |
|---|---|
| Electronic check | More than 45% |
| Credit card / Auto bank transfer | Less than 15% |

> 💡 Electronic check users are 3x more likely to churn than automatic 
> payment users — suggesting lower engagement and commitment level.

---

## 🧠 Retention Recommendations

### High Priority — Target These Customer Groups
| Segment | Why At Risk | Action |
|---|---|---|
| New customers (0–6 months) | 45–50% churn rate | Proactive onboarding program |
| Month-to-month contracts | 55–60% churn | Offer discount for annual upgrade |
| Fiber optic users | 40–42% churn | Investigate service quality issues |
| Customers without add-ons | 35–45% churn | Bundle promotion campaign |
| Electronic check payers | 45%+ churn | Incentivize auto-payment switch |
| Senior citizens | High churn rate | Dedicated support program |

### Strategic Actions
| Strategy | Expected Impact |
|---|---|
| 🔁 Promote multi-year contracts | Reduce churn from 55% to under 5% |
| 📦 Bundle value-added services | Cut churn by up to 60% |
| 🤖 Incentivize auto-payment | Reduce payment-related churn by 3x |
| 🎯 Early-stage engagement | Address 45–50% new customer churn |
| 📞 Senior citizen support | Reduce demographic-specific churn |

---

## 📁 Project Structure

- 🔁 Longer tenure & multi-year contracts
- 📦 Value-added service bundles
- 🤖 Automated payment methods
- 🎯 Proactive early-stage engagement

telecom-customer-churn-EDA/

│

├── 📂 data/

│   └── telecom_churn.csv

│

├── 📂 notebooks/

│   └── churn_analysis.ipynb

│

├── 📂 visualizations/

│   └── churn_charts.png

│

└── README.md
---

## 🔬 Methodology

### Step 1 — Data Loading & Exploration
- Loaded telecom customer dataset
- Explored shape, data types, missing values
- Identified target variable: Churn (Yes/No)

### Step 2 — Data Cleaning
- Handled missing values
- Converted TotalCharges to numeric
- Encoded categorical variables for analysis

### Step 3 — Exploratory Data Analysis (EDA)
- Analyzed churn rate by demographics
- Examined contract type vs churn relationship
- Investigated service bundle impact on retention
- Studied payment method and billing patterns
- Visualized tenure distribution for churned customers

### Step 4 — Business Insights & Recommendations
- Identified top 6 at-risk customer segments
- Developed targeted retention strategies for each segment
- Quantified potential impact of each recommendation

---

## 📊 Dataset

| Field | Detail |
|---|---|
| **Name** | TECO Telecom Customer Dataset |
| **Type** | Customer demographics and service data |
| **Target** | Churn (Yes/No) |
| **Features** | Demographics, contract, services, payment |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python 3** | Data analysis and visualization |
| **Pandas** | Data manipulation and cleaning |
| **Matplotlib** | Chart creation |
| **Seaborn** | Statistical visualizations |
| **Google Colab** | Cloud-based notebook environment |

---

## 🚀 How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/Hashimkhan303/telecom-customer-churn-EDA

# Step 2: Install dependencies
pip install pandas matplotlib seaborn

# Step 3: Open notebook
jupyter notebook notebooks/churn_analysis.ipynb
```

---

## 👨‍💻 Author

**Hashim Khan**

- 🐙 GitHub: [Hashimkhan303](https://github.com/Hashimkhan303)
- 💼 LinkedIn: *(paste your LinkedIn URL here)*
- 🎓 Google Data Analytics Certificate
- 🎓 Google Advanced Data Analytics Certificate

---

## 📄 License

This project uses publicly available telecom customer data.
Built for educational and portfolio purposes only.

---

⭐ **If you found this project useful, please give it a star!**
