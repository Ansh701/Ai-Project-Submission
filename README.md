
# 📊 Employee Sentiment Analysis

## 🔍 Project Overview

This project focuses on analyzing employee emails to evaluate overall sentiment, rank employee engagement, identify flight risks, and forecast sentiment trends using NLP and statistical modeling. The analysis was conducted on an unlabeled dataset (`test.csv`) containing messages exchanged by employees over time.

---

## 🧠 Objectives

- **Sentiment Labeling**: Automatically classify messages as Positive, Negative, or Neutral using NLP techniques.
- **Exploratory Data Analysis (EDA)**: Visualize and understand the dataset structure and sentiment distribution.
- **Monthly Sentiment Scoring**: Aggregate sentiment scores for each employee on a monthly basis.
- **Employee Ranking**: Identify the top three positive and negative employees each month.
- **Flight Risk Detection**: Flag employees who send ≥4 negative messages in any 30-day period.
- **Predictive Modeling**: Use linear regression to forecast future sentiment trends.

---

## 🗂️ Project Structure

```
.
├── Employee_Sentiment_Analysis.ipynb     # Main Jupyter Notebook
├── README.md                             # Summary and project instructions
├── report.docx                           # Final detailed project report
├── visualizations/                       # All saved charts and graphs
└── data/
    └── test.csv                          # Unlabeled dataset
```

---

## 📈 Key Findings

- **Top 3 Positive Employees**:  
  Based on monthly aggregated sentiment scores, the most positively engaged employees were consistently seen contributing optimistic messages.

- **Top 3 Negative Employees**:  
  These employees had the highest number of negative scores and may require further managerial support or HR review.

- **Flight Risk Employees**:  
  Employees flagged due to sending ≥4 negative messages in a rolling 30-day period. This list serves as an early warning signal for disengagement.

---

## 📉 Model Performance

A linear regression model was developed to predict future sentiment trends using features such as time, message frequency, and historical sentiment. Evaluation using metrics like Mean Squared Error (MSE) and R² score indicated the model's moderate effectiveness in trend forecasting.

---

## 🛠️ Tools and Libraries

- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TextBlob / VADER (for sentiment analysis)
- Regex, datetime

---

## 📝 Instructions

1. Open `Employee_Sentiment_Analysis.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells sequentially to process the data, perform analysis, and generate results.
3. View all plots in the `/visualizations` folder and detailed analysis in `report.docx`.

---

## 📬 Submission Notes

**To submit**:  
- Zip the full project folder including all files.
- Send the zip as an email attachment to: **heramb.sawant@glynac.ai**  
- Subject: `AI-project-submission`
- Include your full name in the body of the email.
- Notify via Microsoft Teams once submitted.

---

## 🧾 Summary

This project demonstrates the application of NLP and data science techniques for real-world sentiment analysis in an enterprise setting. The pipeline is designed to scale and can be adapted for live monitoring or HR analytics dashboards.
