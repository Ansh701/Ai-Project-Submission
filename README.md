# 🧠 Employee Sentiment Analysis

**Author:** Ansh Upadhyay
**Project Type:** Internal Evaluation – NLP, EDA, Predictive Modeling  
**Tools & Libraries:** Python, Transformers, Scikit-learn, Pandas, Seaborn, Matplotlib

---

## 📌 Project Overview

This project analyzes internal employee emails to determine sentiment and engagement patterns. It includes NLP-based sentiment classification, monthly scoring, flight risk detection, and a predictive model to forecast sentiment trends using employee communication behavior.

---

## 📂 Contents

- `main.ipynb` — Jupyter Notebook with step-by-step analysis
- `visualizations/` — Graphs and tables
- `final_report.docx` — Comprehensive report
- `README.md` — Project summary

---

## 🧪 Tasks Completed

### ✅ 1. Sentiment Labeling
- Used `distilBERT` transformer model from HuggingFace
- Labeled each email as **Positive**, **Negative**, or **Neutral**

### ✅ 2. Exploratory Data Analysis (EDA)
- Visualized sentiment distribution and trends
- Analyzed employee activity and email volume over time

### ✅ 3. Monthly Sentiment Scoring
- +1 for Positive, -1 for Negative, 0 for Neutral
- Aggregated monthly scores for each employee

### ✅ 4. Employee Ranking
- Identified **Top 3 Positive** and **Top 3 Negative** employees per month
- Sorted by sentiment score, then alphabetically

### ✅ 5. Flight Risk Identification
- Flagged employees sending **≥4 Negative messages** in any **30-day rolling window**
- Generated a list of potential flight-risk employees

### ✅ 6. Predictive Modeling
- Features: message count, average message length, word count
- Built a **Linear Regression model** to predict sentiment scores
- Evaluated using MSE and R²

---

## 🏆 Key Results

### ⭐ Top 3 Positive Employees (Sample)
| Employee | Month | Score |
|----------|--------|-------|
| eric.bass@enron.com | 2010-02 | +2 |
| lydia.delgado@enron.com | 2010-02 | +1 |
| sally.beck@enron.com | 2010-02 | 0 |

### ⚠️ Top 3 Negative Employees (Sample)
| Employee | Month | Score |
|----------|--------|-------|
| john.arnold@enron.com | 2010-02 | -10 |
| kayne.coulter@enron.com | 2010-02 | -6 |
| bobette.riner@ipgdirect.com | 2010-02 | -4 |

---

## 🚨 Flight Risk Employees (Sample)

> Employees who sent 4+ negative emails in a 30-day window:

- john.arnold@enron.com  
- kayne.coulter@enron.com  
- sally.beck@enron.com  
*(Full list in report)*

---

## 📈 Predictive Model Performance

| Metric | Value |
|--------|--------|
| R² Score | `0.XX` *(fill from output)* |
| MSE | `X.XX` *(fill from output)* |

The model shows a moderate correlation between communication behavior and sentiment scores, with potential for expansion using more advanced techniques.

---

## 💡 Insights & Recommendations

- Monitor communication tone as an early warning signal for disengagement.
- Employees with consistently negative tone may benefit from proactive outreach.
- Predictive trends can support HR in identifying sentiment dips early.

---

## 🔁 Reproducibility

1. Clone repo and install dependencies (`transformers`, `sklearn`, etc.)
2. Run `main.ipynb` to regenerate results.
3. Review final report for insights and visual summaries.

---

## 📬 Submission Instructions

- Zipped and emailed to `jbirch@glynac.ai`
- Message sent on Microsoft Teams for evaluation request

---

> ⚠️ **Confidential Internal Evaluation Only**  
> Do not share this project or its data in public repositories.

